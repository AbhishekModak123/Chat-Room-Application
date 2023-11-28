# Chat Room Project

## Introduction
This project consists of a simple chat room application with both server and client components. The server manages multiple client connections, assigns nicknames, and facilitates communication between clients. Clients can connect to the server, enter a chat room, and exchange messages with other users.

## Prerequisites
- Python 3.x

## Usage

### Server
1. Run the server script by executing the following command in the terminal:
    ```bash
    python server.py
    ```
2. The server will start listening for incoming connections on the specified IP address and port.

### Client
1. Run the client script by executing the following command in the terminal:
    ```bash
    python clients.py
    ```
2. Enter the IP address and port number of the server when prompted.
3. Provide a nickname for identification in the chat.

## Features
- Server script listens for incoming connections, assigns nicknames, and handles multiple client connections concurrently.
- Client script connects to the server, sends and receives messages in a chat room setting.
- Threading is used for concurrent message handling on both the server and client sides.

## Usage Notes
- The server binds to the local machine's IP address by default. Modify the `ip_ad` variable in the server script to change this behavior.
- The default port for the server is set to 5679. Modify the `port` variable in the server script to use a different port.
- Messages are displayed in the format: `nickname: message`.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.

## License
This project is licensed under the [MIT License](LICENSE).
