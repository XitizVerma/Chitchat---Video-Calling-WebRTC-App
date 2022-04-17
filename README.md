# Chitchat 💻
A Firebase WebRTC Video Chat App 

In this GitHub repo will use Firebase Cloud Firestore for signalling in a WebRTC Video CHAT Application.
For making the FrontEnd Illustrative we have used CSS Material Design Components.
We will use WebRTC API in our browser and Cloud Firestore as Signaling Server.

The RTC IceCandidate interface—part of the WebRTC API—represents a candidate Interactive Connectivity Establishment (ICE) configuration which may be used to establish an RTCPeerConnection .An ICE candidate describes the protocols and routing needed for WebRTC to be able to communicate with a remote device.

## Steps -

1. For this ,first Create and set up a Firebase project.
2. Enable Cloud Firestore and Create database in the Cloud Firestore pane.
3. Select the Start in test mode.
4. Clone the GitHub repository from the command line:
   ### git clone https://github.com/XitizVerma/Chitchat--Video-Calling-WebRTC-App
5. Install the Firebase Command Line Interface.
   ### npm -g install firebase-tools
   The Firebase Command Line Interface (CLI) allows us to serve our web app locally and deploy our web app to Firebase Hosting.
6. Verify that the CLI has been installed correctly by running the following command:
   ### firebase --version
7. Make sure the version of the Firebase CLI is v6.7.1 or later.
8. Authorize the Firebase CLI by running the following command:
   ### firebase login
9. Associate your app with your Firebase project by running the following command:
   ### firebase use --add
10. When prompted, select your Project ID, then give your Firebase project an alias.
An alias is useful if you have multiple environments (production, staging, etc). However, for this codelab, let's just use the alias of default.
11. You're ready to actually start work on our app! Let's run the app locally!
Run the following Firebase CLI command:
### firebase serve --only hosting

Your command line should display the following response: hosting: Local server: http://localhost:5000
We're using the Firebase Hosting emulator to serve our app locally.

The web app should now be available from http://localhost:5000.
Open your app at http://localhost:5000.

We should see your copy of FirebaseRTC which has been connected to your Firebase project.
The app has automatically connected to your Firebase project.

12. Create a new room
13. Join a new room
14. To stop our NodeJS server from running, we can use the Ctrl+C in the Terminalshortcut which sends the interrupt signal to the Terminal where you start the server.

The development WebRTC server can be accessed by visiting http://localhost:5000.
Running AppRTC locally requires Cloud Firestore Database ,Node.js and compatible Browser.

