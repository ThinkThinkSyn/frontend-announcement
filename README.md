# Frontend Announcement System

## Announcement File Format

Use this format when creating announcement files:

```markdown
---
title: "Your Announcement Title"
date: "YYYY-MM-DD"
author: "Your name"
keywords: ["keyword1", "keyword2"]
level: "info" | "warning" | "error"
summary: "Brief summary of the announcement"
---

Your announcement content in markdown format...
```

### Fields:
- **title**: Brief descriptive title
- **date**: Publication date (YYYY-MM-DD format)
- **author**: Your username/identifier
- **keywords**: Comma-separated tags
- **level**: Severity level (info, warning, error)
- **summary**: Brief summary of the announcement less than 50 words