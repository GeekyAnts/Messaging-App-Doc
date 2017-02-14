# Full Version

Run the following commands on your terminal to setup [React Native Messaging App ](http://market.nativebase.io/view/react-native-messaging-app-with-backend) on your system.


## Installation

* **Opt #1. Download ZIP**

Not familiar with Git?
[Click here](http://gitstrap.com/strapmobile/MessagingApp-with-backend-integration/repository/archive.zip) to download the Full Version of the theme.
Extract the contents of ZIP file after downloading.
Downloading ZIP file does not help you to sync with further updates of [Messaging App](http://market.nativebase.io/view/react-native-messaging-app-with-backend).

* **Opt #2. Clone using GitStrap Web Client**

To setup the Full Version for [Messaging App](http://market.nativebase.io/view/react-native-messaging-app-with-backend) on your system, with **gitstrap** tools to sync your app with constant updates, clone the repo.
[Click here](./gitstrap-tools.md) to clone the theme using GitStrap.

* Install packages for Full Version
```
cd Messaging
npm install
react-native link
```
* After linking all the libraries, create a duplicate of config.example.js as below <br/>
``` cp config.example.js config.js ``` <br/>
Edit the ```config.js``` file to set your own **server URL** and **port number**

* To simulate for iOS
  * **Method One:**
    * Open the project in XCode from ``` ios/messaging.xcworkspace```.
    * Hit Build button to simulate.
  * **Method Two:**
    * Type ``` react-native run-ios ``` in your terminal.

* To simulate for Android
  * Make sure you have an ``` Android emulator ``` installed and running.
  * Type ``` react-native run-android ``` in your terminal.
