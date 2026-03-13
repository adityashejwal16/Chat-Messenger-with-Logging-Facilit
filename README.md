# 💬 Chat Messenger with LOG Facility
📌 Project Description

Chat Messenger with LOG Facility is a simple Client–Server based chat application developed using Java Socket Programming.

This application allows a client and server to communicate in real-time through the terminal.
Messages are sent from the client to the server and from the server to the client continuously until the user exits the chat.

The project demonstrates concepts like:

Socket Programming

Client–Server Communication

Input / Output Streams

Continuous Message Handling

Terminal Based Chat System

⚙️ Features

💬 Real-time messaging between client and server

🔁 Continuous chat loop

🖥️ Terminal-based communication

📡 Uses TCP Socket connection

📝 Displays messages exchanged between users

🔌 Runs on localhost network

🛠️ Technologies Used
Technology	Purpose
Java	Core Programming Language
Socket Programming	Network Communication
Java IO Streams	Input/Output Handling
TCP Protocol	Reliable Data Transfer
📂 Project Structure
Chat-Messenger-with-LOG-Facility
│
├── ChatServerLoop.java
├── ChatClientLoop.java
└── README.md
🧠 Working of the Application
Server Side

Server starts and listens on port 5100.

It waits for a client connection.

Once connected, the server can receive and send messages.

The server reads client messages and replies accordingly.

Client Side

Client connects to localhost port 5100.

After connection, the client sends messages to the server.

The client receives replies from the server.

Communication continues until the client types "end".

📡 System Classes / Functions Used
Class	Purpose
ServerSocket	Creates server listening port
Socket	Establishes client-server connection
PrintStream	Sends messages
BufferedReader	Reads incoming messages
InputStreamReader	Converts byte stream to character stream
▶️ How to Compile and Run
1️⃣ Compile Server
javac ChatServerLoop.java
2️⃣ Run Server
java ChatServerLoop

Output:

Server is waiting at port 5100
3️⃣ Compile Client
javac ChatClientLoop.java
4️⃣ Run Client
java ChatClientLoop

Output:

Client gets connected with server successfully
💻 Example Chat
Client Side
Enter message for server :
Hello Server
Server says : Hello Client
Server Side
Client says : Hello Server
Enter message for client :
Hello Client
🚀 Future Enhancements

📝 Add Chat LOG File Storage

👥 Multi-client support

🖥️ GUI using Java Swing

🔐 Secure messaging

🌐 Network based chat (different machines)

👨‍💻 Author

Aditya Shejwal
