# FlakeIT
A robust chat application that's compatible with web and mobile, on all platforms using iOS, Android and Windows. It uses MeteorJS to make itself extendable.

This application consists o the following use cases,
- Login using Mobile number.
- SMS based verification
- Select contact and start chatting.
- Send Images just like whatsApp
- Use device camera.
- Easy and robust functionality
- Extendable in all platforms.
- Easy updation with direct stack based addition of New Pages

## Installation
 - Download MeteorJS, from here,
    https://www.meteor.com/install

- Open Command Prompt, navigate to where the project is downloaded, Enter the following,

```cd FlakeIT // Navigate to Project directory```
```npm install // Install ```
```meteor // To run the app```

- Open Browser
- Enter, https://localhost:3000

For getting the unique code, after entering your contact number, open CMD, the unique code will be displayed beside your user.

### Running on iOS (Using MAC)
If/ you have a Mac, you can run your app inside the iOS simulator.
Go to your app folder and type:

```meteor install-sdk ios```

This will run you through the setup necessary to build an iOS app from your project. When you're done, type:

```meteor add-platform ios```
```meteor run ios```

You will see the iOS simulator pop up with your app running inside.

### Running on an Android emulator

In the terminal, go to your app folder and type:

```meteor install-sdk android```

This will help you install all of the necessary tools to build an Android app from your project. When you are done installing everything, type:

```meteor add-platform android```

After you agree to the license terms, type:

```meteor run android```

After some initialization, you will see an Android emulator pop up, running your app inside a native Android wrapper.

### Running on an Android device

First, complete all of the steps above to set up the Android tools on your system. Then, make sure you have USB Debugging enabled on your phone and the phone is plugged into your computer with a USB cable. Also, you must quit the Android emulator before running on a device.
Then, run the following command:

```meteor run android-device```

The app will be built and installed on your device.

Use FLAKEIT and enjoy chatting! :)

Made with &#x2764; using MeteorJS
