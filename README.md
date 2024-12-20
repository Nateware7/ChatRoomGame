# Chat Room with Tic Tac Toe Game

This repository contains a simple chatroom application built using Python's `socket`, `threading`, and `tkinter` libraries. The chatroom allows multiple users to connect, chat, and play a game of Tic Tac Toe.

## Features

- **Real-time Chat**: Multiple users can join the chat and send messages to all others.
- **User List**: Displays the list of connected users and allows users to be kicked out of the chat.
- **Ban Users**: Users can be banned by the server.
- **Tic Tac Toe Game**: Players can play a game of Tic Tac Toe within the chatroom interface.

## How It Works

### Server
- A Python server listens for incoming connections from clients.
- It handles client connections and manages broadcasting messages to all connected clients.
- It keeps track of the user list and allows users to be banned or kicked.
  
### Client
- The client is a GUI application built using Tkinter.
- Users enter a username to join the chat and communicate with others.
- The client also features a simple Tic Tac Toe game that users can play together.

## Setup

### Prerequisites

- Python 3.x
- Tkinter (comes pre-installed with Python)
  
### Running the Server

1. Open a terminal and navigate to the server script's directory.
2. Run the server with the following command:


### Running the Client

1. Open a terminal and navigate to the directory containing the client script.
2. Run the client with the following command:

3. Enter a username to join the chat.
4. You can chat with other users and play Tic Tac Toe.

## Commands

- **Kicking a user**: Select a user from the dropdown and click "Kick User" to remove them from the chat.
- **Ban a user**: Banned users will be unable to reconnect to the chat.

## Contributions

Feel free to fork this project and submit pull requests with improvements, bug fixes, or new features!

## License

This project is open source and available under the MIT License.
