# Сhat

The interface consists of a message list and a form for sending messages.



In the list the messages are displayed as:

author: message

author: message

author: message

author: message



The form consists of two instances, the first one contains the name and the second the message.
Running the websocket server locally.

Connect to local server:

`const ws = new WebSocket('ws://localhost:8080');`


Packet format:

`ws.send(JSON.stringify({
username: 'Kirsan',
message: 'Hello world'
}))`