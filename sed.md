# Deleting text
***


## To delete 5 lines after a pattern (including the line with the pattern):
```
sed -e '/pattern/,+5d' file.txt
```

## Remove lines of code with START and END blocks
Sourec: http://serverfault.com/a/137848
```
sed '\:// START TEXT:,\:// END TEXT:d' file
```
