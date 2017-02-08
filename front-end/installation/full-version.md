# Full Version

Run the following commands on your terminal to setup [React Native Messaging App Theme]() on your system.

_**Note:**_ Go through the complete procedure of installation if you wish to include **CodePush** with your app. Otherwise, please skip the steps corresponding to Codepush.

## Installation

* **Opt #1. Download ZIP**

Not familiar with Git?
[Click here](http://gitstrap.com/strapmobile/MessagingApp-with-backend-integration/repository/archive.zip) to download the Full Version of Messaging App.
Extract the contents of ZIP file after downloading.
Downloading ZIP file does not help you to sync with further updates of Messaging App.

* **Opt #2. Clone using GitStrap Web Client**
To setup the Full Version for Messaging App on your system, with **gitstrap** tools to sync your app with constant updates, clone the repo.
[Click here](./gitstrap-tools.md) to clone Messaging App using GitStrap.

* Install packages for Full Version
```
cd Messaging
npm install
react-native link
```

* To simulate for iOS
  * **Method One:**
    * Open the project in XCode from ``` ios/messaging.xcworkspace```.
    * Hit Build button to simulate.
  * **Method Two:**
    * Type ``` react-native run-ios ``` in your terminal.

* To simulate for Android
  * Make sure you have an ``` Android emulator ``` installed and running.
  * Type ``` react-native run-android ``` in your terminal.

_**Note**: If you are building React Native Messaging App Theme with Codepush for first time on your system, please follow ``` Method One ``` to simulate on iOS. (To link the CodePush plugin through Xcode for iOS)_