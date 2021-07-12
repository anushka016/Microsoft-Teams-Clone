# Microsoft-Teams-Clone

This is a video calling app with live chat feature.
The app is developed using node.js framework of Javascript.
To host a video chat, a server has been created using express.js.
Now, to respond to with an HTML file on the server, I used EJS(Embedded Javascript).
Now, for each new user, a unique random URL will be created with the help of UUID library.
A video calling app is based off Real-time communication.
Users send their audio and video stream to all the other users. This is made possible with peer.js.
For impementing WebRTC on the server (for communication between users and server) , I used socket.io.
