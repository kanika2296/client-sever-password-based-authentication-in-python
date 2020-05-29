# Password based authentication
Client-Server program which will facilitate a client to register itself to the server. A server should keep a table of user-hash(password) entry for each user.

This program registers user with username, password and stores password hash in dictonary. Also, when a user tries to login , password validation occurs.

Python,Socket programming 

## IMPLEMENTATION (python3)
SERVER : socket with multithreading
CLIENT : socket
HASH : SHA256 ( using pythons hashlib)

```
INPUT (client side)
1. Username
2. Password
```
```
OUPUT
1. Registeration Successful : new user
2. Connection Successful : password correct
3. Login Failed : password incorrect 

Hash table : Contains User and Password. It is implemented using python Dictionary data structure
```
