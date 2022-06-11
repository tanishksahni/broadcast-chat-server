# broadcast-chat-server
Simple TCP chatroom in Java <br>
A Chatting App made in Java using concepts of Java Networking and Socket Programming that allows communication between a server and client. Here, we set up a socket on each end and allow a client to interact with other clients via the server.
The server-side script will attempt to establish a socket and bind it to an IP address and port specified by the user. The script will then stay open and receive connection requests and will append respective socket objects to a list to keep track of active connections. Every time a user connects, 
a separate thread will be created for that user. In each thread, the server awaits a message and sends that message to other users currently on the chat.
