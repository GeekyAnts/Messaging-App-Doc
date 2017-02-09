# Theming Your App

Customizing Messaging App will be a cakewalk for you. That is due to the fact, we provide you well prepared code shape. This makes it quite simple to be able to dig through the code and hence without problems customizable.

* Messaging App has categorized its screens into different sections.
* Messaging App has a separate file inclusive of color schemes for different sections.
* Messaging App strictly follows programming ethics, hence modifying logo at different locations for your app becomes very simple.
* Messaging App also allows you to customize name for your app.


# Change Components Color

To customize any component of [React Native Messaging App ](http://market.nativebase.io/view/react-native-messaging-app-with-backend) is very easy now.
Follow the [NativeBase ](http://nativebase.io/docs/v0.5.13/customize) procedure to do so.

# Change App logo

Messaging App comes with its logo at login page. To change logo at login page:

* Include image of your logo named as ``` logo.png ```
* Place it under ```/images/```

# Change App Icon

Want to have your own icon for your app? This is very simple with Messaging App.
Follow below given steps to customize app-icon for your app.

* Visit [MakeAppIcon](https://makeappicon.com/) website
* Enter the image of your choice to get logo of various dimensions
* **For iOS:**

    You should upload iOS icons to /ios/messaging/Images.xcassets/AppIcon.appiconset/
* **For Android:**

    * You should upload Android icons along with the folders named as:
        * mipmap-hdpi
        * mipmap-mdpi
        * mipmap-xhdpi
        * mipmap-xxhdpi
    * Upload these folders to /android/app/src/main/res/
* Restart packager and rebuild your app.



# Rename App

Renaming any [React Native](https://github.com/facebook/react-native) app is strenous. But Messaging App proves its flexibility for this approach.
Follow below given steps to rename your app.

* Rename the app name in following files.
    * package.json
    * index.ios.js
    * index.android.js
* This process wipes out the **launchscreen** **and app** icon from your app. Hence you can restore them before moving ahead.

    **iOS:** Restore ```ios/messaging/Images.xcassets```
    **Android:** Restore ```/android/app/src/main/res```
* Delete the **iOS** and **android** directories from your project.
* Run following commands on your terminal:
```  
react-native upgrade
react-native android
react-native link
```

* Overwrite all the files if it prompts.
* Repeat CodePush deployment if you want to include it in your app.
* Try simulating now.




To be updated soon . . .
