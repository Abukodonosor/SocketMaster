# SocketMaster
lib for easy managing with web-sockets

This is a beta library for a management socket, based on send and receive mechanism.

All server logic is temporary placed in app.js file.
(examples how to send and receive message)

Client class is placed ad public/javascripts/SocketMasterClient.js,
and examples of usage of this class can be find under views/index.ejs

idea*
-implement redis support for chatRooms
-(redis cluster, with node cluster) allow communication between users from different instances
- support:direct messages, group chanels, datachanel for exchanging the data [string, json, buffer]




