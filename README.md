# Java Chatting Application

This is a chatting application implemented in Java using Swing for the graphical user interface and Socket programming for the communication between client and server.

![image](https://github.com/umangmtiwari/Java-Chatting-Application/assets/143312015/212edaa9-3873-407f-8d34-e030fb1e107c) ![image](https://github.com/umangmtiwari/Java-Chatting-Application/assets/143312015/9da58cc0-feee-4ccc-99e9-35cbbde159a7)

![image](https://github.com/umangmtiwari/Java-Chatting-Application/assets/143312015/54b0cbf7-01b2-4015-9aa8-fcc88803451a) ![image](https://github.com/umangmtiwari/Java-Chatting-Application/assets/143312015/c60429c5-56a2-4176-aa99-e1d9334853b0)

## Features

- Real-time chatting between client and server
- GUI built with Java Swing
- Simple and intuitive interface

## Prerequisites

- Java Development Kit (JDK) installed
- An IDE or text editor to edit and run Java code

## Getting Started

### Running the Server

1. Open the `server.java` file.
2. Compile and run the server code:

   ```sh
   javac server.java
   java chatting.application.Server
   ```

### Running the Client

1. Open the `client.java` file.
2. Compile and run the client code:

   ```sh
   javac client.java
   java chatting.application.Client
   ```

### How to Use

1. Start the server by running the `Server` class.
2. Start the client by running the `Client` class.
3. Enter your message in the text field at the bottom and click "Send" to send the message.

## Code Explanation

### Client

The client code handles the user interface and sends messages to the server.

### Server

The server code listens for incoming client connections and handles the received messages.

## UI Components

- `JFrame`: Main window for the application
- `JPanel`: Panels to organize the layout
- `JTextField`: Text field for user input
- `JButton`: Button to send messages

## Networking Components

- `Socket`: For client-server communication
- `ServerSocket`: For server to listen for incoming connections
- `DataInputStream` and `DataOutputStream`: For reading and writing messages
