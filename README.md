# ChatApplication
The Java Socket Chat Application is a single client-server chat application that allows a client to connect to a server, login, and engage in real-time text-based communication.

## Features

- *Login Authentication*: The client is required to login with a username and password before accessing the chat functionality.
- *Real-Time Communication*: Once logged in, the client can send and receive text messages in real-time, facilitating interactive communication.
- *User-friendly Interface*: The client-side interface provides a user-friendly chat window for composing and displaying messages.
- *Message Broadcasting*: When the client sends a message, the server broadcasts it back to the same client, allowing for a simple chat-like interaction.
- *Server Administration*: The server includes basic administration capabilities, such as monitoring the client connection and managing client disconnections.
- *Single-Client Support*: The application is designed to handle a single client connection at a time, enabling one-on-one communication between the client and server.
- *Cross-Network Communication*: The client and server can be run on the same system or on different systems connected to the same network, allowing communication over local or wide-area networks.

## Prerequisites

- Java Development Kit (JDK) installed on your system.

## How to Run

To run the Java Socket Chat Application, follow these steps:

### Running the Server

1. Open a command prompt or terminal.
2. Navigate to the directory where the `server.java` file is located.
3. Compile the `server.java` file by executing the following command:
   
   javac server.java
   
4. Run the server by executing the following command:
   
   java server
   
   This will start the server and make it listen for client connections.

### Running the Client

1. Open a separate command prompt or terminal.
2. Navigate to the directory where the `client.java` file is located.
3. Compile the `client.java` file by executing the following command:
   
   javac client.java
   
4. Run the client by executing the following command:
   
   java client
   
   This will launch the client application.
5. When prompted, enter the IP address or hostname of the system where the server is running.
6. Enter the port number on which the server is listening (default port is often 5000 or any port you have specified in the `server.java` code).
7. Once connected to the server, the client will be prompted to enter a username and password for authentication.
8. After successful login, the client can start sending and receiving messages through the chat interface.

Please note that if you are running the server and client on different systems, you need to ensure that they are connected to the same network, and the client is provided with the correct IP address or hostname of the server system.

## Conclusion

The Java Socket Chat Application provides a simple and interactive way to explore socket programming concepts. By running the server and client components, you can experience real-time communication and exchange text messages securely with login authentication. This application serves as a foundation for understanding the fundamentals of client-server architectures, network communication, and user authentication.

Feel free to provide any additional instructions or clarify any specific points if needed.
