# Course Name 
# (Made by: Mayank Singh Rajput (B19CSE054) & Mohit Ahirwar (B19CSE055)
.
.
.
.
## Instructor: Dr. Suchetana Chakraborty (Assistant Professor, Department of Computer Science & Engineering @ Indian Institute of Technology, Jodhpur)

## MPC Project - EmoChat
.
.
.
.
### Steps to Run
For running the app, we have to first download the code file (if in zip format, just extract it).
* Open the terminal in that directory (either dedicated or your fav. code editor’s terminal) and run the following commands ```npm install``` and ```npm install --global expo-cli```.
* Note that the command to install expo cli is a global command so it can be run in any directory of the system.
* Now let the processes run and install the required files.
* After that, we can simply run the app using the command ```npm start```.
* This will either redirect us to a browser window or give an URL that can be copied and pasted to open a browser window.
* In that window, we will find a QR code and some links to run the app. Make sure to navigate the selected option to **tunnel** instead of “LAN” to enable a stable connection. The app might not run on the “LAN” option.
* We have to download the Expo client app - **Expo Go** from the play store in order to scan and run that app on our smartphone or any android emulator for that matter.
* After scanning, let it download the contents and the app will be ready to rock!
.
.
.
.
## App Description

This mobile app is a chat app which can predict emotions based on live chats. When the user sends or receives a message, he/she can see the sentiment that might be displayed by that message.
Creation of this app used following technologies. (see report for detailed description)

### Front-end
* React Native
* Expo
* Androd Emulator

### Back-end
* Firebase
* Ml Model

The app looks like the following screenshot,

![image](https://github.com/mynk-rjpt/emo-chat/blob/main/screenshots/Chats.png)

.
.
.
.

## How to run webapp using Docker in your system?
```sh
1. install docker in your system, and login to it, and run the docker desktop before continuing.
2. Clone the repo using the following command
git clone https://github.com/garvitchughiitj/M20CS018.git
3. Change directory to the folder.
cd M20CS018
4. Build the docker image using, 
docker build . -t m20cs018 
5. Run the image
docker run -it -p 8000:80 m20cs018
6. Access the webapp on 
http://localhost:8000/gg/
```
