FTP Client–Server Application (Java)

This repository contains a Java-based FTP (File Transfer Protocol) client–server application with graphical user interfaces. The system enables file transfer between a client and a server using socket programming and multithreading.


🚀 Features

Client–Server communication using Java Sockets

Graphical User Interfaces (GUI) for both client and server

File transfer functionality from client to server

Multithreaded server to handle multiple client connections

Modular and object-oriented design

🧩 Components Overview
🔹 WelcomeInterface.java

Initial GUI screen

Allows users to choose between Client or Server mode

🔹 FTPServerUI.java

Server-side GUI

Starts the server and listens for incoming client connections

🔹 ServerThread.java

Handles individual client connections

Enables concurrent file transfers using multithreading

🔹 FTPClientUI.java

Client-side GUI

Allows users to connect to the server and select files for transfer

🔹 FileSender.java

Manages file reading and transmission over sockets

Ensures reliable data transfer between client and server

🛠️ Technologies Used

Java

Java Swing (GUI)

Socket Programming

Multithreading

IntelliJ IDEA (project configuration included)

▶️ How to Run the Project
Prerequisites

Java JDK 8 or higher

IntelliJ IDEA (recommended) or any Java IDE

Steps

Clone the repository:

Open the project in IntelliJ IDEA

Run WelcomeInterface.java

Start the Server

Launch the Client and connect using the server’s IP and port

Select and send files from the client to the server

📌 Notes

Ensure the server is running before starting the client

Firewall settings may affect socket communication

This project is suitable for learning:

Networking fundamentals

Java GUI applications

Multithreaded systems
