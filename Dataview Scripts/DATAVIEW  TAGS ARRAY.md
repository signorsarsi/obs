```dataview

TABLE  file.mtime as "modified", file.etags as "tags"
FROM -"Templater" and -"SDATA" 
WHERE tags >""
SORT file.mtime desc
```