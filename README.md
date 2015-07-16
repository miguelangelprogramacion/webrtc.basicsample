WebRTC basis sample: Peer-to-peer web chat

Websocket/Java signalign server and html/js client.

Examples taken from [1]

Run server: 

mvn clean package
mvn exec:java -Dexec.mainClass="world.we.deserve.WebRTCSignalingServer"

After execution, it's important to ensure that websocket is closed.

Client:

Just open websocket-client.html.

[1] WebRTC Cookbook by Andrii Sergiienko
