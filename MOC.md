---
date_created: Friday, July 4th 2025, 9:45:16 pm
date_modified: Saturday, July 5th 2025, 11:21:02 pm
---
# MOC
Map of Content (MOC) for my Obsidian Vault. Lists All notes that exist by type. Queries can be modified using Dataview.
## People MOC

This Dataview table lists all notes about **People**, sorted by last modified date.

```dataview
table birth_date as "Birth Date", death_date as "Date of Death", role as "Role"
from "Permanent"
where type = "Person"
sort file.name asc
```

## Concepts MOC

This Dataview table lists all notes about **People**, sorted by last modified date.
```dataview
table religious-tradition as "Tradition", periods as "Periods"
where type = "Topic"
sort file.name asc
```