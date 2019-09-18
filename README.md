# Sprint-1
# BioFuture Research group Object Detection Android Demo
 
 This is a camera app that continuously detects the objects (bounding boxes and classes) in the frames seen by your device's back camera, using a quantized [MobileNet SSD, model trained on the [COCO dataset](http://cocodataset.org/). These instructions walk you through building and running the demo on an Android device.

 The model files are downloaded via Gradle scripts when you build and run.

 <!-- TODO(b/124116863): Add app screenshot. -->

## Build the demo using Android Studio

### Prerequisites

* If you don't have already, install **[Android Studio](https://developer.android.com/studio/index.html)**, following the instructions on the website.

* You need an Android device and Android development environment with minimum API 21.
* Android Studio 3.3 or later.

### Building
* Open Android Studio, and from the Welcome screen, select Open an existing Android Studio project.

* If it asks you to do a Gradle Sync, click OK.

* You may also need to install various platforms and tools, if you get errors like "Failed to find target with hash string 'android-21'" and similar.
Click the Run button (the green arrow) or select Run > Run 'android' from the top menu. You may need to rebuild the project using Build > Rebuild Project.

* If it asks you to use Instant Run, click Proceed Without Instant Run.

* Also, you need to have an Android device plugged in with developer options enabled at this point. See **[here](https://developer.android.com/studio/run/device)** for more details on setting up developer devices.


