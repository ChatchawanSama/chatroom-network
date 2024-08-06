## TCP-chatroom
# How To Run?

# Server
gcc server.c -o server
./server

# Client
You can run many clinet to join the group chat
gcc client-multithreaded.c -lpthread -o client
./client localhost
