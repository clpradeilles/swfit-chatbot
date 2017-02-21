
# Watson Developer Cloud iOS SDK: Chat App Example

This repository contains an example application to demonstrate how developp a Chat in a Swift application based on [Watson Developer Cloud iOS SDK](https://github.com/watson-developer-cloud/ios-sdk).

This example modifies the [JSQMessagesViewController](https://github.com/jessesquires/JSQMessagesViewController) demo application to add Watson services, including Speech to Text, Conversation, and Text to Speech.

_Please note that this project is still a work-in-progress!_

### Requirements

- Xcode 7.3+
- iOS 8.0+

### Dependency Management

This project uses both [Carthage](https://github.com/Carthage/Carthage) and [CocoaPods](https://cocoapods.org/) to manage dependencies.

- Install Carthage using [Homebrew](http://brew.sh/): `brew install carthage`
- Install CocoaPods: `sudo gem install cocoapods`

### Getting Started

1. Clone the repository: `git clone https://github.com/clpradeilles/swift-chatbot-ReadyToUse`
2. Build the dependencies: `carthage update --platform iOS`
3. Open `ChatApp.xcworkspace`
4. Update your service credentials in `Credentials.swift`
5. Add framework that you have install in your app
6. Build and run the app!
