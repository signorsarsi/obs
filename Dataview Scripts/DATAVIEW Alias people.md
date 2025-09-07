```dataview
TABLE  file.mtime as "modified", file.ctime as "created", aliases as "aliases"
FROM "" WHERE contains(aliases,"Sinan")
SORT file.mtime desc
```

