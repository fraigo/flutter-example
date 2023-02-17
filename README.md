# flutter_example

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


# Tutorial

* Install Requirements
    * Install Flutter SDK https://docs.flutter.dev/get-started/install
    * Install VS Code https://code.visualstudio.com/download
    * Install Flutter/Dart VSCode Extensions
    * For MacOS
        * Install Xcode (Simulator and build tools)
* Create a flutter app
    * `flutter create flutter_example`
    * `cd flutter_example`
* Edit `pubspec.yaml` 
    * Set your app name (lowercase) 
    * Set app description (free text)
* First Run of your app
    * To run iOS app on MacOS
        * Run `open -a Simulator` to run the iOS simulator (iOS App)
        * Connect your phone using USB cable
    * Run `flutter run`
        * If multiple devices are available, select the one you want to run the app (MacOs, iOS, web, Android)
        * For iOS device, you may need to provide first app signing details (organization)
            * Run `open ios/Runner.xcworkspace`
            * Go to the Project 'Signing and Capabilities' tab and setup the Team and a valid Bundle identifier
            * Run `flutter run` again. The compilation process could ask you for Keychain access (enter user password)
        * On MacOs, if you get a warning for `iproxy`:
            * Open the flutter installation folder on Finder `open /path/to/flutter/`
            * Navigate to `bin/cache/artifacts/usbmuxd`
            * Click on the `iproxy` app icon and allow to Open the app
            * Run `flutter run` again
    * To stop the application run console, press `Ctrl+C`


        
        

    
