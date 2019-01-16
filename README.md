# WebSocket


# WebSocket using ws module
    1. -> require ws module and chain a server instance
        Syntax:
            var WebSocketServer = require(ws).server;
    2. -> create a new instance of WebSocketServer
      Syntax:
            var wss = new WebSocketServer({ port:3000 });
    3. -> insall ws module
        Syntax:
            npm install ws --save