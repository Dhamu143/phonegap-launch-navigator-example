Cordova/Phonegap Launch Navigator Example
=========================================

This repo contains example projects illustrating how to use the [Launch Navigator plugin](https://github.com/dpa99c/phonegap-launch-navigator) to launch native navigation apps on iOS, Android, and Windows to get driving directions to a desired location.

<!-- START table-of-contents -->
**Table of Contents**

- [Downloading](#downloading)
- [Projects](#projects)
- [Building and running](#building-and-running)
  - [Android](#android)
  - [iOS](#ios)
  - [Windows](#windows)
  - [WP8](#wp8)
- [Credits](#credits)
- [License](#license)

<!-- END table-of-contents -->
 
# Downloading

To download the example, clone the repo using git:

    $ git clone https://github.com/dpa99c/phonegap-launch-navigator-example.git

# Projects

The repo contains the following example projects in sub-directories:

- SimpleExample - a basic example showing how the plugin can be invoked to navigate to a specified destination, with an optionally specified start location.
- AdvancedExample - a more complex example which shows how the plugin can be used to launch specific navigation apps and how their input parameters can be tailored.
- IonicExample - a basic example using Ionic framework / AngularJS

# Building and running

Each example project can be built for running on your local machine by opening a terminal in one of the example project directories and running commands as follows:

## Android

To run an example project on Android using the Cordova CLI:

    $ cordova run android

## iOS

To run an example project on iOS using the Cordova CLI:

    $ cordova run ios

Note: For this to work, you need to install [ios-deploy](https://github.com/phonegap/ios-deploy) first: `npm install -g ios-deploy`

## Windows

To run an example project on Windows Universal (8.1/10) using the Cordova CLI:

    $ cordova run windows

Note: This will run the app on your Windows PC. For this to work, you need at least Visual Studio 2013 Community: http://www.visualstudio.com

Or import the project in Visual Studio 2013 and run it from there. Within Visual Studio, you will be able to choose between Windows Phone 8.1 and Windows 8.1/10 PC.
The Visual Studio 2013 project is located here:

    LaunchNavigatorExample/platforms/windows/CordovaApp.sln

## WP8

To run an example project on Windows Phone 8.0 using the Cordova CLI:

    $ cordova run wp8

Note: This will run the app in your Windows 8.0 or 8.1 phone. For this to work, you need at least Visual Studio 2013 Community: http://www.visualstudio.com

Or import the project in Visual Studio 2013 and run it from there.

	LaunchNavigatorExample/platforms/wp8/LaunchNavigatorExample.sln



# Credits

Thanks to [opadro](https://github.com/opadro) for Windows platform example

License
================

The MIT License

Copyright (c) 2016 Dave Alden /  Working Edge Ltd.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.