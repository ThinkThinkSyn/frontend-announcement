# Frontend Announcement System

## Structure

Each announcement is organized in a folder containing:
- `metadata.md` - Common metadata shared across all languages
- `en.md` - English version with title and summary
- `zh-cn.md` - Simplified Chinese version with title and summary
- `zh-hk.md` - (Deprecated) Traditional Chinese version with title and summary
- `zh-tw.md` - Traditional Chinese version with title and summary.

## File Format

### metadata.md
Common metadata for all language versions:

```markdown
---
date: "YYYY-MM-DD"
author: "Your name"
keywords: ["keyword1", "keyword2"]
level: "info" | "warning" | "error"
banner: true | false
is_active: true | false
---
```

### Language files (en.md, zh-cn.md, zh-hk.md, zh-tw.md)
Language-specific content:

```markdown
---
title: "Your Announcement Title"
summary: "Brief summary of the announcement"
---

Your announcement content in markdown format...
```

### Fields:
- **date**: Publication date (YYYY-MM-DD format)
- **author**: Author username/identifier
- **keywords**: Array of tags for categorization
- **level**: Severity level (info, warning, error)
- **banner**: Whether to display as a banner
- **is_active**: Whether the announcement is currently active
- **title**: Language-specific title
- **summary**: Language-specific summary (less than 50 words)