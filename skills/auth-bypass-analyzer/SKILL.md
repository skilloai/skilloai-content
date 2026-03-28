---
name: auth-bypass-analyzer
description: "Identify and analyze authentication and authorization bypass points"
category: web-exploitation
tags: ["ctf", "security", "web", "auth", "bypass"]
---

# Auth Bypass Analyzer

## Purpose
Systematically analyze the authentication and authorization logic of a web application to identify bypass points (e.g., IDOR, session fixation, or weak JWT secrets).

## Steps
1. **Session Management Audit**: Inspect cookie attributes (e.g., `HttpOnly`, `Secure`, `SameSite`) and session token generation/expiration.
2. **Authorization Mapping**: Identify access controls for different user roles (e.g., user vs admin) and test for Improper Direct Object References (IDOR).
3. **Logic Flaw Discovery**: Probe common bypass techniques like parameter pollution, response manipulation, or time-of-check-time-of-use (TOCTOU) flaws.

## Output
- Identified auth bypass vulnerabilities.
- Analysis of session management flaws.
- Logic-based bypass strategy.
