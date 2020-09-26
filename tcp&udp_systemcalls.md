# TCP
Hier die systemcalls, die benötigt werden, um eine TCP Verbindung zu öffnen:
## Client
```c
socket()
-> connect()
recv()
send()
close()
```

## Server
```c
socket()
-> bind()
-> listen()
-> accept()
send()
recv()
close()
```

# UDP 
Hier die systemcalls, die benötigt werden, um eine TCP Verbindung zu öffnen:
## Client
```c
socket()
-> bind()
revfrom()
sendto()
close()
```


## Server
```c
socket()
-> bind()
recvfrom()
sendto()
close()
```
