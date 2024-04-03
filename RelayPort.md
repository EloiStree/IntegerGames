Current public ip: 81.240.94.97  
Local IP: 192.168.1.69  
  
(🤝 require: Singed Handshake RSA)  
(🤖 Easy to use, but first to be disable during DOS attack)  
  
This array is want I would like and not what is currently implemented.  

| #   | Port| Description                         |    |        |
| --- | -----| -------------------------------     | -- |------|
|X | 4500 | RSA SETUP WEBSOCKET                 |🤝    | Use to set your account from your RSA key|
|X | 4501 | RSA OPEN INTEGER WEBSOCKET          |🤝    | Use to change integer |
|X | 4502 | RSA OPEN INTEGER UDP PUSH ONLY    |🤝🤖| Use to change integer  |
|X | 4503 | RSA INTEGER GAMES LINE BROADCAST    |🤝    | LINE and Key:Value emitted by the game of the stream |
|X | 4504 | RSA INTEGER GAMES BYTES BROADCAST   |🤝    | BYTES of object requiring 30 FPS UPDATE and are essential to the game|
|X | 4505 | RSA INTEGER CHANGED BROADCASTER     |🤝     |Allows to listen to a specific integer change if you have the key|
|X | 4506 | PUBLIC INTEGER CHANGED            |  🤖  |Allows to listen to all integer set as public without RSA key|
|X | 4507 | RSA WEBSITE TO SERVER               |🤝    |RESERVE TO PUSH WEBSITE ACTION TO RELAY|
|X | 4508 | RSA BRIDGE CLOUD TO RELAY           |🤝    |RESERVE TO BUILD BRIDGE|
|X | 4580 | LOCAL RELAY WEBSITE                 |    |Landing page Of the relay|
|X | 4588 | SOCKET IO WEBTRANSFER               |🤝?    |WEBSOCKET IO SERVER IN NODE JS|
|X | 4510 | OPEN TWITCH PLAY IN Websocket       |    🤖|OPEN WHEN TWITHC PLAY TYPE OF GAME ACCEPTING TEXT|
|X | 4511 | OPEN TWITCH PLAY IN UDP TEXT        |    🤖|OPEN WHEN TWITHC PLAY TYPE OF GAME ACCEPTING TEXT|
|X | 4512 | OPEN TWITCH PLAY WEBSOCKET BROADCAST|    🤖|OPEN TO HAVE GAME CONTEXT INFO FROM THE GAME IN TEXT FORMAT|
|X | 4513 | OFFLINE ML STUDIO |🤝    🤖|OPEN TO HAVE GAME CONTEXT INFO FROM THE GAME IN TEXT FORMAT|
|X | 4514 | OFFLINE WHISPER   |🤝    🤖|OPEN TO HAVE GAME CONTEXT INFO FROM THE GAME IN TEXT FORMAT|
|X | 4520 | RSA ADD INTEGER EXACT TIMING SYNC |🤝|ADD INTEGER TO BE CHANGE AT AN EXACT TIMING TO THE MILLISECONDS |
|X | 4521 | FRIEND INTEGER EXACT TIMING SYNC |🤖|ALLOWS YOUR FRIEND TO LISTEN TO THE INTEGER CHANGE AND PREPARE FOR THE CHANGE|
