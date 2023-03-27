bidirectional communication between a client and a server
-->use a single TCP connection fortraffic in both directions

The WebSocket [[protocol]] attempts to address the goals of existing bidirectional HTTP technologies in the context of the existing HTTP infrastructure


client, server
handshake : server accept to transfer data wit the client, a key is used such that only connections that are websockets connections are accepted
data transfer : two-way communication channel where each side can, independently from the other, send data at will

the server has to prove to the client that it received the client's WebSocket handshake

opening handshake-->prove handshake is recieved, closing handshake-->no more data exchanged or recieved

---
Resources
- [RFC websocket](https://www.rfc-editor.org/rfc/rfc6455.html#section-1)