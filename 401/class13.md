# 🗒️ Class 13: Message Queues

## Readings

###  Socket.io Chat Example

- Explain to a non-technical recruiter what the Chat Example (above) does.
  > The example in the Socket.io Chat Example reading allows its users to send messages to each other. 

- What proof of life are we getting on the backend from the above app?
  > Listening on *: 3000

- Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a - message to everyone except for a certain emitting socket?
  > To send a message to everyone except the sender, you would use `socket.broadcast.emit`


### Rooms

- What is a room and how might a room be useful?
  > A room is a socket channel.

- How do you join a room?
  > By using `socket.join`

- how do you leave a room?
  > By calling the `disconnect` event


### Namespaces

- What is a Namespace and what does it allow you to do?
  > A namespace is a specific chanmnel that lets you split the logic of the application and allows for `multiplexing`

- Each namespace potentially has its own what? (hint: 3 things)
  > `Event Handler`, `room`, and `middleware`.

- Discuss a possible use case for separate namespaces
  > One possible use case for using separate namespaces is if we want to create seperate "rooms/channels" that have restricted access.
