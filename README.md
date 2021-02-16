# Cli-Chat App

A simple Command Line Interface Python Chat Application,This simply creates a Chatroom in which a server and clients can send and receive messages from each other.

Created using SocketServer Framework

# Usage

```bash
git clone https://github.com/nishanth023/Cli_chat
```
Run server.py with correct parameters:

```bash
./server.py [PORT] [HOST]
```

You can also run directly, in that case it defaults to 10000 localhost:

```bash
./server.py 
```

Afterwards clients can connect to the server using client.py with correct parameters, Usage:

```bash
./client.py [PORT] [HOST]
```

Default is again, 10000 localhost:
```bash
./client.py 
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
