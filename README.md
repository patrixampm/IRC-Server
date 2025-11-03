# IRC-Server

An IRC server implementation, in C++98, to chat with friends through terminal or hexchat.

## Build

```
make
```

## Usage

```
./irc <port> <password>
```

If connecting through terminal:
```
nc <hostname> <port>
```

Then:
```
PASS <password>
NICK <your_nickname>
USER <your_username> 0 * <your_realname>
``

## Clean

```
make clean    # Remove object files
make fclean   # Remove all build artifacts
make re       # Rebuild from scratch
```

You can create channels, chat with other users, change modes, kick people out of chats and many other fun IRC things!
