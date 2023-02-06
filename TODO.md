# TODO
Pages that have been linked to but haven't yet been created:
```dataview
TABLE
FLATTEN file.outlinks as Note
WHERE !(Note.file) AND !contains(meta(Note).path, "/") AND !contains(file.path, "Upcoming")
GROUP by Note
SORT Note ASC
```
