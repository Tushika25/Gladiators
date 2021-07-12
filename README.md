# Gladiators
# microsoftEngage_2021


Teams Clone : Gladiators! 
(A project built understanding tough situations faced by teachers, students and professionals during video meetings and solve them.)

Hosted on https://www.gladiatorswin.com/

# Main Website 
![Example Image](https://github.com/Tushika25/Gladiators/blob/main/Main%20website.png)




# Features :

- Video Call Feature : Allows multiple people to connect to rooms and talk to each other.
- Room creation Feature: Creates room for different set of people as per their requirements.
- Screen Sharing Feature : Gladiators also allows you to share screen during the video call.
- Chat Feature : There is also a chat feature which allows you to send text messages to each other.
- No.of participants Feature: Shows total number of participants in the room.
- Active Participants Feature: shows the participants name who are active in the room.
- Live Coding Feature: A coding IDE where all the people connected to a room can code simultaneously.
- Code IDE with syntax highlighting Feature: Allows you to choose from a set of multiple languages and compilers, and highlights syntax on the basis of them. Also takes in customized input, runs the code and gives output.
- Drawing palette Feature: The interface also consists of a whiteboard which all the members in the room can use to draw stuff. 
- The whiteboard also contains multiple features like colorful pens, pens of different sizes, clear canvas, redo and undo drawing options.

Total Number of incorporated features : 14.
For detailed Demo and complete documentation refer to the 'Documentation' file in the repo.

# Video page :
![Example Image](https://github.com/Tushika25/Gladiators/blob/main/Video%20page.png)


# Implementation Details :

Main Backend : Python Flask;
FrontEnd : HTML + CSS + JS

- Video call feature is implemented using Twilio API and WebRTC Technology, so as to implement webRTC in python (flask)
- Live coding is implemented using cloud firestore of Google Firebase which makes the changes in real time.
- Coding IDE is based on Ace.js javascript library, and executing is done using Judge0 API hosted on sntc servers.
- Drawing Palette is implemented using WebSockets technology.
- Other features such as Join Room, Leave room etc are also implemented using Flask and WebSockets
- Chat feature is also implemented using WebSockets.

# Agile Methodologies Used : 

The first thing done was planning for the course of 4 weeks. The plan implemented took into account the SCRUM process wherein the whole process was broken down into 3 important parts. 
•	Software devcycle: This part included dividing the time period into Sprints of 1-2 weeks each. Each sprint was planned beforehand at the start (Sprint planning). I devoted the first two weeks (first sprint) in writing the starting code and making a basic layout of the product web app with few basic and the most important features. 
•	Work Breakdown: This part includes solving bugs and incorporating deliverables. I devoted the third week (second sprint) in solving the bugs I faced (one was in the code IDE and other one in the screen sharing) thus working on Product Backlogs. I gave the fourth week (last sprint) to incorporating few new features and trying to incorporate the adapt feature into my web app.
•	Roles and responsibilities: SCRUM recognizes in teams, 2 groups of members. During my project I was the person who was managing both the chicken and pig team by doing the managerial aspects and code part of the project.
Also, another process of agile methodology allowed me to write code that didn’t require much changes so as to incorporate new features. 
The following mural image shows the whole summary of 4 weeks.

![Example Image](https://github.com/Tushika25/Gladiators/blob/main/agile%20(2).png)
# How to run the project

- Clone the project
- This Project Requires Python3 to run, so make sure to install it.
- Install the libraries using `pip install -r prerequisites.txt`
- Run the app using `flask run`.
- The project runs on localhost:5000
