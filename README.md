# 🐉 TCP Server and Client in (pure) C
A very simple server and client written in pure C that communicate using the Transport Control Protocol over Internet Protocol.
This was made as an implementation of TCP Sockets as part of CS206.

# Technologies
- C

# Features
- Send and receive messages over the Internet using TCP
- Customizable port numbers as per usage

# Learning Outcomes
Over the course of this project, I learnt:

 1. the workflow of `socket()`, `bind()` , `listen()`,  `accept()` and then `recv()` for the server
 2. the workflow of `socket()`, `connect()` and then `send()` for the client
 3. the error-free (😅 and tiresome) implementation of TCP Sockets

# How do you run it?
1. Clone the repository (make sure you are on a Linux machine)
2. Run `gcc server.c -o server.out`
3. Run `gcc client.c -o client.out`
4. Run both the executables on different instances of a terminal with a message as an argument for `./talk.out`

# Preview

![TCP Server](https://github.com/user-attachments/assets/bff68eb0-3661-4f44-976b-cb43ede6255c)


  
