
# Dockerized Socket.IO Chat Demo

A simple chat demo for Socket.IO

## How to use

```
docker run -p 3000:3000 bwstearns/socketio-chat
```


_OR_

```
$ npm i
$ npm start
```

_OR_

```
docker build -t socketio-chat .
docker run -p 3000:3000 socketio-chat
```

And point your browser to `http://localhost:3000`. Optionally, specify
a port by supplying the `PORT` env variable.

## Features

- Multiple users can join a chat room by each entering a unique username
on website load.
- Users can type chat messages to the chat room.
- A notification is sent to all users when a user joins or leaves
the chatroom.
