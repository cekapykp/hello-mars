# hello-mars
React-native Setup Guide

Installing dependencies : You will need Node, Watchman, the React Native command line interface, Xcode and CocoaPods.

1 - You should install this : https://brew.sh

2 - Run the following commands in a Terminal after installing Homebrew:
  
     brew install node
     brew install watchman

3 - Xcode : 
  The easiest way to install Xcode is via the Mac App Store.

3.5 - Command Line Tools : 
  You will also need to install the Xcode Command Line Tools. Open Xcode, then choose "Preferences..." from the Xcode menu. Go to the Locations panel and install         the tools by selecting the most recent version in the Command Line Tools dropdown. 

3.9 - Installing an iOS Simulator in Xcode : 
  To install a simulator, open Xcode > Preferences... and select the Components tab. Select a simulator with the corresponding version of iOS you wish to use.

4 - CocoaPods :
  CocoaPods is built with Ruby and it will be installable with the default Ruby available on macOS. You can use a Ruby Version manager, however we recommend that you use the standard Ruby available on macOS unless you know what you're doing.

       sudo gem install cocoapods
       
NOTE : if you are using M1 mac air pro, you must this :
  1 - Open your Terminal under Rosetta and run sudo gem install ffi in terminal.
  2 - Open Finder > Applications > Utilities > Terminal > Right Click > Get Info > Open Using Rosetta
