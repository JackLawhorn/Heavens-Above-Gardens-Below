---
dg-publish: true
---
# Upcoming

Ideas that have been mentioned but haven't been created just yet:
```dataview

TABLE
FLATTEN file.outlinks as Note
WHERE !(Note.file) AND !contains(meta(Note).path, "/") AND !contains(file.path, "Upcoming")
GROUP by Note
SORT file.name ASC

```
