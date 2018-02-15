# TheMedicalMuseum
This repository contains a Unity 3D mobile application for iOS and Andriod devices called **_The Medical Museum_**. . It has been built and tested using the Google Cardboard Viewer. **_The Medical Museum_** is a one level scene designed to be a virtual museum. The user can move around the museum to read about the new ideas and practices virtual reality plans to bring to the medical industry. The application uses a groudraycasting mechanic for the user to move around the room by looking towards the floor and pressing the clicker on the Google Cardboard Viewer. This scene includes 3D models, videos and audio sources. So, make sure to keep your sound on your mobile device to learn something new visually and audibly!
![screen shot 2018-02-09 at 4 08 11 pm](https://user-images.githubusercontent.com/35173600/36050215-a69e1320-0db3-11e8-9afa-204c6f31f832.png)

## Getting Started

### Prerequisites
The software you will need to download in order to build and run the game on a mobile device:
<br /> • The cross-platform engine [Unity 3D](https://unity3d.com/unity/qa/patch-releases/2017.1.0p4 "Unity 3D download") Patch Release 2017.1.0p4
<br />
- For iOS builds, the latest version of [Xcode](https://developer.apple.com/download/ "Xcode 9.3 Beta")
- NOTE! You will need to have an [Apple ID](https://appleid.apple.com/account#!&page=create "Developer Account") in order to download Xcode and build for iOS
- NOTE! Make sure to have the latest software version; 11 and up!
- For Android builds, you need [Android Studio](https://developer.android.com/studio/index.html "Android Studio download") and the [Java JDK 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html "JDK download")

### Installing
To build and run a copy of this application to your mobile device:
<br />
<br /> • On the **_The Medical Museum_** repository, go to the green "Clone or download" button and click "Download Zip"
<br />
<br /> • Once the zip file has loaded onto your desktop, double click the zip file to open. Navigate to the folder Assets > The Night at the Museum.unity and double click the scene to open it in Unity 3D
<br />
<br /> -NOTE! The scene may not be located at the top of the folder. If not, you will have to scroll through the folder to find it. It will be titled exactly The Night at the Museum.unity with the Unity logo-
<br />
<br /> After opening the scene in Unity 3D choose to build to either an iOS or Android mobile device
<br />
1. For iOS builds:
   - Go to File > Build Settings and switch the platform to iOS (this can take a while) then click the Player Settings button below that and with this open you can change the name of the application and bundle identifier, if you would like to change them, before pressing Build and Run to then be prompted to name the build and save it. (I usually save the build to my desktop so I can delete it later) 
     - The build will open in Xcode. Make sure to check your Apple ID is correct, the bundle identifier and the name of the application is what you would like it to be (again, you are more than welcome to use the default name) then press the play button in the upper left corner and the application will build and run directly to your iOS device.
2. For Android builds:
   - First, go to the top left corner and click Unity > Preferences. Then, select External Tools in the list and add the locations of Android Studio and Java JDK 8 in the correct section.
     - Afterwards, go to File > Build Settings and switch platform to Android (this can take a while to do) then click the Player Settings button below that and you can change the name of the application and bundle identifier, if you would like to change them, before pressing Build and Run to then be prompted to name the build and save it. The application will be built right to your Android device from Unity. 

### Deployment
When building the application to your phone a few important things to note:
<br />
<br /> • In Player Settings, you are able to not only change the name of the application and bundle identifier to whatever you would like you can also add a photo to be the icon for the application on your phone. It will be one of the first things you can do in Player Settings. Right under renaming the application.
<br /> • The Google VR SDK used in the game tracks your head movement. Meaning, where ever the phone is facing, the application will open and start your game from that position. If you would like to be facing a certain direction to play the game right after building to your phone I would suggest facing your device in that direction and hold it horizontally so you can start the experience in the most comfortable position for you.

## How to play
The instructions to play the application **_The Medical Museum_**: (instructions are also displayed on the games start panel)
![screen shot 2018-02-09 at 4 08 36 pm](https://user-images.githubusercontent.com/35173600/36050232-bb2b652c-0db3-11e8-8e4a-81b7dcad63a0.png)
<br />
<br /> • Read the start panel and press the "Check In" button to start the experience
<br />
<br /> • You can move by looking towards the ground until you see the purple cylinder. Then, use the Cardboard clicker to click and move anywhere you would like through the meseum
<br />
<br /> • There are several displays and the user can go up to any exhibit to learn something new VR is planning to bring to change the medical industry
<br />

# Authors
• Samantha Cayla Bajis - _Initial work_ - SamBajis

# Acknowledgments
To make **_The Medical Museum_** possible:
<br /> 
<br /> • Udacity - coding for user movement mechanic
<br /> 
<br /> • Google VR SDK- head tracking, sound system and ability for the users interaction with the Google Cardboard Viewer
