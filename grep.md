# Check for existance conditionally

example 1
```
if grep --quiet MYSQL_ROLE=master /etc/aws/hosts.conf; then
  echo exists
else
  echo not found
fi
```

example 2
```
guest_check=$(grep "guest account = nobody" "/etc/samba/smb.conf")
```
