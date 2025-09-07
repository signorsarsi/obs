```dataview

TABLE  file.mtime as "modified", file.ctime as "created"
FROM -"Templater" and -"SDATA" and #entry or #concept

SORT file.mtime desc
```

