# Gladiators
# microsoftEngage_2021

Project Submission:

Teams Clone : Gladiators! (A platform where you can video call, code and draw together)

Hosted on https://suhanaaaina.wixsite.com/gladiators


# Features :

- Video Call Feature : Allows multiple people to connect to rooms and talk to each other.
- Screen Sharing Feature : Gladiators also allows you to share screen during the video call.
- Chat Feature : There is also a chat feature which allows you to send text messages to each other.
- Live Coding : A coding IDE where all the people connected to a room can code simultaneously.
- Code IDE with syntax highlighting : Allows you to choose from a set of 5 languages and compilers, and highlights syntax on the basis of them. Also takes in customized input, runs the code and gives output.
- Drawing palette : The interface also consists of a whiteboard which all the members in the room can use to draw stuff. The whiteboard also contains multiple features like colorful pens, pens of different sizes, clear canvas, redo and undo drawing options.


# Implementation Details :

Main Backend : Python Flask;
FrontEnd : HTML + CSS + JS

- Video call feature is implemented using Twilio API and WebRTC Technology, which is one of the easiest and the best ways to implement webRTC in python (flask)
- Live coding is implemented using cloud firestore of Google Firebase which makes the changes in real time.
- Coding IDE is based on Ace.js javascript library, and executing is done using Judge0 API hosted on sntc servers.
- Drawing Palette is implemented using WebSockets technology.
- Other features such as Join Room, Leave room etc are also implemented using Flask and WebSockets
- Chat feature is also implemented using WebSockets.

# How to run the project

- Clone the project
- This Project Requires Python3 to run, so make sure to install it.
- Install the libraries using `pip install -r prerequisites.txt`
- Run the app using `flask run`.
- The project runs on localhost:5000
