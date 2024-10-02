# ft_irc
ft_irc is a project that aims to create a functional IRC server. It implements the basic functionalities of an IRC server, allowing multiple clients to connect, join channels, and communicate with each other. This project deepens understanding of network programming, socket manipulation, and the IRC protocol.
## Installation 
1. Clone repository:
   ```
   git clone git@github.com:clemllovio/IRC.git
   ```
2. Navigate to the project directory and compile

## Usage 
To start the IRC server:
```
./ircserv <port> <password>
```
• `<port>`: The port number on which your IRC server will listen for incoming connections.

• `<password>` : The connection password.

## IRC Client Connection
You can connect to your IRC server using IRC client like netcat or HexChat.

#### Example of connection with netcat:
```
nc localhost 6667
```

Then, authenticate and set your nickname:
```
PASS secretpassword
NICK yournickname
USER username hostname servername:realname
```

## Limitations
• This is a basic implementation and may not include all features of a full IRC server.

• It may not be compatible with all IRC clients or implement all RFC specifications.

## Credits
This project was developed by Lisa Ciullo, Aymeric Jakubczyk and Clémence Llovio as part of the curriculum at 42 School. 
