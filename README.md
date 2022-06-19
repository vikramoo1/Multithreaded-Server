# Multithreaded-Server

## Description
  Chat application written in C++ that uses sockets and multi-threading to communicate among multiple users.
  A simple client and a server can be used to send and receive messages using socket programming in C++. On top of that, we use multithreading to allow communication among multiple users.
  
 ## How to run the project
 
The project folder contains four files, client and server cpp code, and client and server executable files (for linux).
This project involves OS specific libraries and hence can be compiled in linux only.

To compile run the following commands in command line(terminal):

1.g++ server.cpp -lpthread -o server

2.g++ client.cpp -lpthread -o client

3.To run the server, type ./server

4.To run the client, type ./client

5.To simulate multiple users, open up a new command line window and type ./client
 
