# People MOC

This Dataview table lists all notes about **People**, sorted by last modified date.

```dataview
table file.name as "Person", file.mtime as "Last Modified"
from "Permanent"
where contains(file.tags, "#Person")
sort file.mtime desc
```