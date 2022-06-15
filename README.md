Custom Adapter Sample App
============

This app demonstrates how to create and use a ListView and custom ArrayAdapter (called FlavorAdapter) to display a custom list item view that contains an ImageView and two TextViews.

![App Screenshot](http://lh3.googleusercontent.com/ZKdSHN5puyfe3SySFz9_ufbtFUihW90DEr5OXx8_sNsGSzblqIZkEZjrps0MMH_Z77ik_BEkKAzDk7968uM=s0#w=360&h=640)



How to use this repository
--------------
- Fork this repository to your Github account.
- Open Android Studio 3.2.x+ in your local machine.
- We recommend you to use the [Version Control System](https://developer.android.com/studio/intro#version_control_basics)(VCS) in your Android Studio 3.2.x+ IDE to clone the repository directly in your IDE.
- You may have to use the File > Settings > Version Control (VCS) menu option to set up Git settings.
- Refer to this [IntelliJ document](https://www.jetbrains.com/help/idea/version-control-integration.html) for details.
- Working with VCS will make it easy for you to push your updates or switch between branches to your remote repository in Github.

Prerequisites
--------------
Android Studio 3.2.1 or higher
- Android SDK API v32 (For AndroidX dependencies, the min compileSdkVersion version is 31)
- minSdkVersion 21
- Supports up to Android 12
- Gradle 7.2.0

To run app in an Android Virtual Device (AVD), we have used the following configuration:
- Pixel 4 Mobile device with x86 System image
- API level 31
- Android 12

Note - Gradle Updates
---------------
The Android Studio build system depends on Gradle and its plugins. The Gradle and its plugins have to be updated separately of Android Studio.
For the updated version, refer to the following updated files:
~/build.gradle (project) file
~/app/build.graddle(: app) file
~/gradle/wrapper/gradle-wrapper.properties file
You can refer anytime to the latest [Android Gradle plugin release notes](https://developer.android.com/studio/releases/gradle-plugin) for the newest version of plugins.


Getting Started
---------------

This sample uses the Gradle build system. To build this project, use the "gradlew build" command or use "Import Project" in Android Studio.


Patches are encouraged, and may be submitted by forking this project and
submitting a pull request through GitHub. Please see CONTRIBUTING.md for more details.

License
-------

Copyright 2016 Google, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.
