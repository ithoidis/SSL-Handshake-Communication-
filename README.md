# SSL-Handshake-Communication
Server-Client communication pattern over SSL Handshake


1) Server
Compile: 
```
gcc -Wall -o server Server.c -L/usr/lib -lssl -lcrypto
```
Run:  
```
sudo ./server <portnum> 
```
2) Client
Compile: 
```
gcc -Wall -o client Client.c -L/usr/lib -lssl -lcrypto
```
Run: 
```
./client <hostname> <portnum> 
```
