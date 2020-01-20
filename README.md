# RNAppGEO

## Setup environment:
### Node & Watchman
We recommend installing Node and Watchman using Homebrew. Run the following commands in a Terminal after installing Homebrew:

    brew install node
    brew install watchman

If you have already installed Node on your system, make sure it is Node 8.3 or newer.

Watchman is a tool by Facebook for watching changes in the filesystem. It is highly recommended you install it for better performance.

### Xcode & CocoaPods
The easiest way to install Xcode is via the Mac App Store. Installing Xcode will also install the iOS Simulator and all the necessary tools to build your iOS app.

If you have already installed Xcode on your system, make sure it is version 9.4 or newer.

Command Line Tools
You will also need to install the Xcode Command Line Tools. Open Xcode, then choose "Preferences..." from the Xcode menu. Go to the Locations panel and install the tools by selecting the most recent version in the Command Line Tools dropdown.

Xcode Command Line Tools

Installing an iOS Simulator in Xcode
To install a simulator, open Xcode > Preferences... and select the Components tab. Select a simulator with the corresponding version of iOS you wish to use.

CocoaPods
CocoaPods is built with Ruby and it will be installable with the default Ruby available on macOS. You can use a Ruby Version manager, however we recommend that you use the standard Ruby available on macOS unless you know what you're doing.

Using the default Ruby install will require you to use sudo when installing gems. (This is only an issue for the duration of the gem installation, though.)

    sudo gem install cocoapods

For more information, please visit CocoaPods Getting Started guide.


## Running your React Native application
Run npx react-native run-ios inside your React Native project folder:

cd RNApp/ios
    
    pod install
    
cd RNApp
    
    npx react-native run-ios

You should see your new app running in the iOS Simulator shortly.

npx react-native run-ios is one way to run your app. You can also run it directly from within Xcode.

Refer to
https://facebook.github.io/react-native/docs/getting-started

GEO library:
https://facebook.github.io/react-native/docs/geolocation#__docusaurus
https://github.com/Agontuk/react-native-geolocation-service
