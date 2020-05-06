# ChatApp

Websocket is a communication protocol that establishes a two way messaging between client and server.
I will be using a branch of the websocket called STOMP (Streaming Text Oriented Messaging Protocol)
HTTP Handshake.  WebSocket does have limitations because HTTP uses ports 80 & 443 and because firewalls block other ports. So HTTP Handshake is used to communicates to the server that it is not HTTP and to upgrade to the WebSocket and then will be able to form a connection.
Not all browers support WebSocket protocol.  
To account for this problem SockJS will be activated as a fallback for these browsers.


