## TCP-chatroom

### How To Run?

#### Server

1. Compile the server program:
   
   ```sh
   gcc server.c -o server
    ./server

2. Compile the client program: Client
    You can run many clinet to join the group chat
   
   ```sh
    gcc client-multithreaded.c -lpthread -o client
    ./client localhost
