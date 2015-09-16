# Deleting text
***


### To delete 5 lines after a pattern (including the line with the pattern):
```
sed -e '/pattern/,+5d' file.txt
```

### Remove lines of code with START and END blocks
Sourec: http://serverfault.com/a/137848
```
sed '\:// START TEXT:,\:// END TEXT:d' file
```

# Appending text
***

### Append line after match
```
sed  '/\[option\]/a Hello World' input
```
### Append after match
```
sed '/PATTERN/ a NEW-LINE-TEXT' FILE
```
### Insert line before match
```
sed  '/\[option\]/i Hello World' input
```
