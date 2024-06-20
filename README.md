# frontend

## Prerequsites:

### In Development machine
1. node version > 18
2. npm version > 8
3. expo-cli
4. You may need the Android SDK as well. Xcode is not needed for IOS development.

### For testing in android
1. Expo Go app
<br><b>Note:</b> Sometimes it is installed automatically if you have the device connected via adb and run the project.

### For testing in IOS
1. Expo Go app
<br><b>Note:</b> Download from app store and connect with the camera app.
*************************************

## To run the program

PWD: Project Root dir

Step 1: Install all the required packages
<code>
yarn set version berry
yarn install
</code>

You will find it in the node_modules folder.

Step 2: Make sure either you are running an android/IOS emulator or connected a device. 
<br>For more information:
<br>[Android Emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
<br>[IOS Emulator](https://docs.expo.dev/workflow/ios-simulator/)
<br>[USB connected android device](https://developer.android.com/studio/run/device#developer-device-options)

Step 3: Build and run the program<br>
a. For Android
<code>
yarn start --android
</code>

b. For IOS
<code>
yarn start --ios
</code>

c. For Web
<code>
yarn start --web
</code>