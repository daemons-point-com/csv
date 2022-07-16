Notizen
=======

MD nach CSV
-----------

```
$ grep -v "^-*|" 001.md | tr '|' ',' | sed -e 's/\s*,\s*/,/g' >002.csv
```
