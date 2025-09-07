```dataview
TABLE  file.mtime as "modified", file.ctime as "created"
FROM -"Templater" and -"SDATA" 

SORT file.mtime desc
```

