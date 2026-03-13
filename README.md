# 💬 Chat Messenger with LOG Facility

## 📌 Project Description

Chat Messenger with LOG Facility is a simple Client–Server based chat application developed using Java Socket Programming.

This application allows a client and server to communicate in real-time through the terminal.
Messages are sent from the client to the server and from the server to the client continuously until the user exits the chat.

| Concepts Demonstrated       |
| --------------------------- |
| Socket Programming          |
| Client–Server Communication |
| Input / Output Streams      |
| Continuous Message Handling |
| Terminal Based Chat System  |

---

## ⚙️ Features
| Feature                                          |
| ------------------------------------------------ |
| 💬 Real-time messaging between client and server |
| 🔁 Continuous chat loop                          |
| 🖥️ Terminal-based communication                 |
| 📡 TCP socket connection                         |
| 📝 Message display between users                 |
| 🔌 Runs on localhost network                     |

---

## 🛠️ Technologies Used
| Technology         | Purpose                   |
| ------------------ | ------------------------- |
| Java               | Core Programming Language |
| Socket Programming | Network Communication     |
| Java IO Streams    | Input and Output Handling |
| TCP Protocol       | Reliable Data Transfer    |

## 📂 Project Structure
| File                | Description                                     |
| ------------------- | ----------------------------------------------- |
| ChatServerLoop.java | Server program that waits for client connection |
| ChatClientLoop.java | Client program that connects to server          |
| README.md           | Project documentation                           |

---

## 🧠 Working of the Application
| Server Side                               |
| ----------------------------------------- |
| Server starts and listens on port 5100    |
| Server waits for client connection        |
| After connection server receives messages |
| Server sends response to client           |

| Client Side                            |
| -------------------------------------- |
| Client connects to localhost port 5100 |
| Client sends message to server         |
| Client receives reply from server      |
| Chat continues until client types end  |


## 📡 System Classes Used
| Class             | Purpose                                  |
| ----------------- | ---------------------------------------- |
| ServerSocket      | Creates server listening port            |
| Socket            | Establishes client-server connection     |
| PrintStream       | Sends messages                           |
| BufferedReader    | Reads messages                           |
| InputStreamReader | Converts byte stream to character stream |

## ▶️ How to Compile and Run
| Step           | Command                   |
| -------------- | ------------------------- |
| Compile Server | javac ChatServerLoop.java |
| Run Server     | java ChatServerLoop       |
| Compile Client | javac ChatClientLoop.java |
| Run Client     | java ChatClientLoop       |

## 💻 Example Communication
| Client Side              | Server Side                 |
| ------------------------ | --------------------------- |
| Hello Server             | Client says Hello Server    |
| Server says Hello Client | Server replies Hello Client |

## 🚀 Future Enhancements
| Feature              | Description                      |
| -------------------- | -------------------------------- |
| Chat Logging         | Store chat messages in log file  |
| Multi Client Support | Allow multiple clients           |
| GUI Interface        | Build interface using Java Swing |
| Secure Chat          | Add encryption                   |
| Network Chat         | Connect multiple systems         |

## 👨‍💻 Author
Aditya Dipak Shejwal
