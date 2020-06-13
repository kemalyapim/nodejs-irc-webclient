# nodejs-irc-webclient

A simple IRC-Webclient based on node.js and socket.io. Thus it uses websockets
for the communication between node.js server and the browser.

Most of the functionality is implemented to be run at the client side. This
enshures that user can only break their own client if they try to modify them.
Furthermore this means less stress for the server.

Start with:
node irc_gateway.js [port]
