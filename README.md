# MULTITHREADED-CHAT-APPLICATION




DESCRIPTION:
Overview:
This Java-based chat application enables real-time messaging between multiple clients using Sockets and Multithreading. The system consists of a server that listens for incoming connections and clients that communicate through the server. It supports multiple users simultaneously by handling each client on a separate thread.

Key Features
✅ Real-Time Communication – Clients can exchange messages instantly.
✅ Multi-Client Support – The server handles multiple users using threads.
✅ Broadcasting – Messages sent by one client are relayed to all others.
✅ Error Handling – Handles disconnections and unexpected input gracefully.
✅ Simple and Efficient – Uses core Java networking (Socket, ServerSocket).

How It Works
1. The server (ChatServer.java) starts, listening on a predefined port.
2. Clients (ChatClient.java) connect to the server and can send messages.
3. Each client runs on a separate thread, enabling multiple users to chat simultaneously.
4. Messages are broadcasted to all connected clients in real-time.
5. If a client disconnects, the server removes them and continues operation.

Technologies Used
1. Java (Core Java, Multithreading, Exception Handling)
2. Sockets (ServerSocket for server, Socket for clients)
3. I/O Streams (BufferedReader, PrintWriter for message exchange)

OUTPUT: 
![Screenshot 2025-02-18 150513](https://github.com/user-attachments/assets/665d46e2-7a12-422d-b66f-d946508206c4)
