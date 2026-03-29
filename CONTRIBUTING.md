# Contributing to Promptraft Skills

Thank you for wanting to contribute! Promptraft is a community-driven marketplace for high-quality, reusable AI prompts (skills). 

To ensure consistency and scalability, every skill must follow these rules.

## 📦 Folder Structure

All skills live in the `/skills/` directory grouped by their unique slug.

```text
skills/
  └── <skill-slug>/
      └── SKILL.md
```

### Slug Rules:
- Lowercase only.
- Hyphen-separated (no spaces or special characters).
- Example: `react-performance-debugger`

## 📝 Markdown Format (SKILL.md)

Every skill **MUST** have a `SKILL.md` file with a YAML frontmatter header and a Markdown body.

```markdown
---
name: Skill Name
description: A short, punchy description (150 chars max).
tags: [tag1, tag2]
author: Your Name (optional)
date_added: YYYY-MM-DD
---------------------------------

Your well-engineered prompt goes here.
Use clear instructions and professional language.
```

## 🚀 How to Contribute

1. **Fork** the repository.
2. **Create a new folder** in `/skills/` using the slug rules.
3. **Add your SKILL.md** using the [SKILL_TEMPLATE.md](./SKILL_TEMPLATE.md).
4. **Validate**: Ensure your prompt is high-quality and provides real value.
5. **Submit a Pull Request**.

## ⚠️ Validation Rules
Your skill will be automatically skipped if it is missing:
- `name`
- `description`
- `tags`
- `prompt content` (minimum 50 characters)

We look forward to seeing your powerful prompts!
