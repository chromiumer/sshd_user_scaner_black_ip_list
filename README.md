# sshd user scaner black ip list


```
grep "Failed password"  /var/log/secure| awk '{print $(NF-3)}'| sort| uniq
```
