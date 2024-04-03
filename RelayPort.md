
- Local IP: 192.168.1.69
  
(🤝 require: Singed Handshake RSA)
(🤖 Easy to use, but first to be disable during DOS attack)

This array is want I would like and not what is currently implemented.
| #   | Port3| Done| Description                         |    |        |
| --- | -----| -| -------------------------------     | -- |------|
| 2   | 4500 |X| RSA SETUP WEBSOCKET                 |🤝    | Use to set your account from your RSA key 🤝|
| 4   | 4501 |X| RSA OPEN INTEGER WEBSOCKET          |🤝    | Use to change integer 🤝|
| 6   | 4502 |X| RSA OPEN INTEGER UDP PUSH ONLY    |🤝🤖| Use to change integer  |
| 8   | 4503 |X| RSA INTEGER GAMES LINE BROADCAST    |🤝    | LINE and Key:Value emitted by the game of the stream |
| 10  | 4504 |X| RSA INTEGER GAMES BYTES BROADCAST   |🤝    | BYTES of object requiring 30 FPS UPDATE and are essential to the game|
| 12  | 4505 |X| RSA INTEGER CHANGED BROADCASTER     |🤝     |Allows to listen to a specific integer change if you have the key|
| 14  | 4506 |X| PUBLIC INTEGER CHANGED            |  🤖  |Allows to listen to all integer set as public without RSA key|
| 16  | 4507 |X| RSA WEBSITE TO SERVER               |🤝    |RESERVE TO PUSH WEBSITE ACTION TO RELAY|
| 18  | 4508 |X| RSA BRIDGE CLOUD TO RELAY           |🤝    |RESERVE TO BUILD BRIDGE|
| 20  | 4580 |X| LOCAL RELAY WEBSITE                 |    |Landing page Of the relay|
| 22  | 4588 |X| SOCKET IO WEBTRANSFER               |🤝?    |WEBSOCKET IO SERVER IN NODE JS|
| 24  | 4510 |X| OPEN TWITCH PLAY IN Websocket       |    🤖|OPEN WHEN TWITHC PLAY TYPE OF GAME ACCEPTING TEXT|
| 26  | 4511 |X| OPEN TWITCH PLAY IN UDP TEXT        |    🤖|OPEN WHEN TWITHC PLAY TYPE OF GAME ACCEPTING TEXT|
| 28  | 4512 |X| OPEN TWITCH PLAY WEBSOCKET BROADCAST|    🤖|OPEN TO HAVE GAME CONTEXT INFO FROM THE GAME IN TEXT FORMAT|
| 28  | 4513 |X| OFFLINE ML STUDIO |🤝    🤖|OPEN TO HAVE GAME CONTEXT INFO FROM THE GAME IN TEXT FORMAT|
| 28  | 4514 |X| OFFLINE WHISPER   |🤝    🤖|OPEN TO HAVE GAME CONTEXT INFO FROM THE GAME IN TEXT FORMAT|
