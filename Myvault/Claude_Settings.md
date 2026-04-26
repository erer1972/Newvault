# Claude Settings & Preferences

## Vault Assistant Behavior

- **Language**: Respond in Turkish unless note content is in English
- **Format**: Use Obsidian markdown — `[[wikilinks]]`, `#tags`, frontmatter YAML
- **Style**: Concise, structured notes with clear headings
- **Links**: Always suggest relevant `[[internal links]]` to existing vault notes

## Frontmatter Template
```yaml
---
title: Note Title
date: YYYY-MM-DD
tags: [#category, #subcategory]
status: active | archived | draft
related: [[Note1]], [[Note2]]
---
```

## Preferred Note Types

| Type | Folder | Template |
|------|--------|----------|
| Daily | 01_Daily/ | Daily_Note_Template.md |
| Project | 02_Projects/ | Project_Template.md |
| Meeting | 03_Work/ | Meeting_Notes_Template.md |
| Research | 05_Knowledge/ | Research_Template.md |
| Book | 05_Knowledge/ | Book_Review_Template.md |

## Do Not
- Create Docker or container configurations
- Add build systems or package managers
- Modify `.git/` or vault settings files
- Create files outside the defined folder structure
