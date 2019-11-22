# Flappy Bird

React Native implementation of the classic Flappy Bird game using react-native-game-engine and Matter.js

**Running the project**

1. `npm install`
2. `cd ios && pod install && cd ..`
3. `react-native run-ios`

*** Android and WSL ***

0. install npm to WSL (Ubuntu) according to [installation instructions](https://github.com/nodesource/distributions/blob/master/README.md#installation-instructions)
1. in WSL `npm install` resolve dependencies according to [React Native CLI Quickstart -> Linux -> Android](https://facebook.github.io/react-native/docs/)
2. in Windows: connect android phone and start adb in CMD `adb devices -l`
3. in WSL `npx react-native run-android --variant=release`

**How it looks like**

<img src="https://miro.medium.com/max/600/1*0LsQWoD1CWdgwsY-4ir-ZA.gif" width="200" />

**Video Walkthrough**

- [Part #1](https://www.youtube.com/watch?v=qBGnfULn8W4)
- [Part #2](https://www.youtube.com/watch?v=XzLekeXt-Bg)

**Medium Blog Post:**
[Read on Medium](https://medium.com/better-programming/making-a-production-ready-flappy-bird-in-react-native-751713661a60)
