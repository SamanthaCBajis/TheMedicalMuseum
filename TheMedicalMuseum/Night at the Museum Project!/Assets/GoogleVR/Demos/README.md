# Google VR SDK for Unity - Demo Scenes

Copyright (c) 2016 Google Inc. All rights reserved.

## Headset Demo Scene

File: **Assets/Gvr/DemoScenes/HeadsetDemo/DemoScene.unity**

This demo is a simple scene that uses the headset with gaze input (without a
controller). The "game" consists of locating the cube and clicking the viewer's
trigger button.  Compatible with a traditional Cardboard viewer.

## Controller Demo Scene

File: **Assets/Gvr/DemoScenes/ControllerDemo/ControllerDemo.unity**

This is a demo of how to use the controller. Running this scene on an
actual phone requires an Android N build running on a supported VR device (for
example, a Nexus 6P), and a controller or controller emulator.

If you want to run the scene in the Unity Editor only, you only need a
phone with the controller emulator installed.

For instructions on how download and set up your controller emulator, see
the information about controller support in
[https://developers.google.com/vr](https://developers.google.com/vr).

Summary:

  * The controller phone can be running any version of Android supported
    by the controller emulator app (Lollipop and above, at the time of this
    writing).
  * Install the controller emulator app on the controller phone.

To run the scene in the Unity Editor:

  * Make sure you have the Android SDK installed, and that the ``adb``
    command is in your PATH environment variable.
  * Connect your controller phone to your computer with a USB cable.
  * Verify that you are correctly set up by typing ``adb devices`` on
    a terminal. That should list your device.
  * Click Play on the Unity Editor.

To run the scene on your headset phone:

  * You will need two phones, one for the headset and one to use as a
    controller emulator.
  * The headset phone must be running an Android N build.
  * Set up a WiFi hotspot on your controller phone, and have your headset
    phone connect to it (remove your SIM card if you want to avoid mobile
    data charges).
  * Make sure you've gone through the necessary setup steps to enable
    controller emulator support on your headset phone (in particular,
    verify that **Enable Controller Emulator** is enabled in
    **Google VR Services Settings**).
  * Launch the Controller Demo scene on the headset phone.

How to play:

  * Point at cubes using your controller or controller emulator.
  * Hold the controller's touchpad as you move your controller to drag the
    cubes around the scene.
  * Repeat until happiness is achieved.

Note: the controller can only be used on a supported VR-enabled Android device
(at the time of this writing, the Nexus 6P) running a VR-enabled build of
Android N (the latest Android N developer preview build). On any other
device or platform (e.g. unsupported Android device, iOS, desktop, etc), the
controller API will still be present, but will always report the controller as
being disconnected.



Samantha Bajis's Night at The Medical Museum Project:

Welcome to The Medical Museum!

This scene uses the Gvr Unity SDK Version 1.60.0.
The scene uses the movement mechanic Ground Raycasting to move around the scene.
The scene was created using Unity on a Mac laptop then built and run to an iPhone (IOS) device.
The scene was then played on a Google Cardboard headset and has been built specifically for that headset.

To run this scene in the Unity Editor:

* Unzip file,and click to open "SamBajisNightMuseum" folder> Assets>"The Night at the Museum.unity" scene.
* Unity will open and click the file with the same name to open the scene.
* Click the Play button on the top middle of the screen to play in the Game View on desktop. 

To run this scene on your headset mobile:

* Please make sure you have the IOS SDK installed.(If not go to Build Settings> Select IOS platform in list>
Switch Platform and load)
* Nagivate to Build Settings> Player Settings> Other settings.
* Enable "Virtual Reality Supported" and choose Google Cardboard from "Virtual Reality SDKs" "dropdown.(if it has not been done already)
* Change Bundle Identifier to something personal to differentiate from other applications.
* Run build in XCode and install to device.


This scene is created to spread knowledge of the impacts of Virtual Reality technology in the Medical Industry.

This scene is designed to look like a museum disguised as a therapy/doctors' office to relate to the content.

How to play The Medical Museum:

1. Read the Panel in front of you and click the "Check In Here" Button to begin.
2. To move around the scene, look at the floor until you see the pink cylindar icon.
   Then, click in any direction on the floor you would like to go and you will move there.
   Continue this action to move around the scene.
    If you would like to get the best view to read the exhibits in the scene, direct the pink cylinder
   toward one of the six white circles on the floor for the specific exhibit.


Credit is given below to all the assets/movements/models/materials/sounds used to create this scene:

Udacity; https://www.udacity.com/ and http://www.udacityvr.com/downloads/

Unity; https://unity3d.com/

The Unity Asset Store; https://www.assetstore.unity3d.com/en/

Google Images; https://images.google.com/

freeSFX; http://www.freesfx.co.uk



Credit is given below to all the reading/information/article sources used to create this scene:

Virtual reality and pain management: current trends and future directions; https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3138477/

10 ways virtual reality is revolutionizing medicine and healthcare; http://www.techrepublic.com/article/10-ways-virtual-reality-is-revolutionizing-medicine-and-healthcare/

Wikipedia; https://en.wikipedia.org/wiki/Virtual_reality_therapy

Virtual Reality, Coming to a Dentist's Office Near You; https://virtual.reality.news/news/virtual-reality-coming-dentists-office-near-you-0156289/

The revolutionary way virtual reality is curing phobias; http://www.news.com.au/technology/innovation/inventions/the-revolutionary-way-virtual-reality-is-curing-phobias/news-story/e71e4648c711e698e1164fdb6e8efa30

Virtual Reality Therapy to Treat the World's Most Common Vision Problem; https://www.youtube.com/watch?v=QSPqeudhjto
