# Get Started

System Requirements:

* Globally installed [node](https://nodejs.org/en/)&gt;= 6.3.1

* Globally installed [npm](https://www.npmjs.com/)&gt;= 3.10.3

* Globally installed [mongodb](https://docs.mongodb.com/)&gt;=3.4.1

#### Installation:

* **Opt \#1. Download ZIP**: Not familiar with Git? [Click Here](http://gitstrap.com/strapmobile/MessagingApp-Backend/repository/archive.zip) to download the Full Version of MessagingApp. Extract the contents of ZIP file after downloading. Downloading ZIP file does not help you to sync with further updates of [Messaging App](http://market.nativebase.io/view/react-native-messaging-app-with-backend).

* **Opt #2. Clone using GitStrap Web Client**
To setup the Full Version for [Messaging App](http://market.nativebase.io/view/react-native-messaging-app-with-backend) on your system, with **gitstrap** tools to sync your app with constant updates, clone the repo.
[Click here](../front-end/installation/gitstrap-tools.md) to clone the theme using GitStrap.

* #### Run these commands on your terminal:

    ```
    [user@localhost] $ cd <folder-name>

    [user@localhost] $ npm install

    [user@localhost] $ npm start
    ```

    Before you perform ``` npm start ``` ,you need to configure a few authorization tokens that will be used in your app. Follow the below mentioned steps:

    * SignUp on [Twilio](https://www.twilio.com/) platform to obtain **accountSid** ,**authToken** and obtain a mobile number from [Twilio](https://www.twilio.com/).

    * SignUp on [OneSignal](https://onesignal.com/) platform to obtain your **app_id** and **Authorization token** for your app.

    * Rename the file ``` MessagingApp-Backend/config/secretToken.example.js ``` to ``` MessagingApp-Backend/config/secretToken.js``` and enter your obtained credentials .

* #### Open another terminal and fire the following commands to initiate mongod:

    ```
          [user@localhost]$  mongod
    ```
