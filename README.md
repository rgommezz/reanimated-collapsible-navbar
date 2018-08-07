# reanimated-collapsible-navbar

Small demo to show how to implement a collapsible navigation bar in React Native, with all the animations running on the UI thread and without the JS thread having to intervene. The GIF below showcases how the JS thread is intentionally frozen and still the snapping animation gets executed after the gesture release.

## Article explaining the code
https://medium.com/@rgommezz/reanimating-your-react-native-experience-d1377d51118a

![collapsiblenavbar3](https://user-images.githubusercontent.com/4982414/43739544-c16401fa-99c8-11e8-8f3c-0ef1da21ac6e.gif)


## Note for the future
I haven't been able to put together a snack/expo, because even though react-native-reanimated (the main dependency) is already bundled up with expo, the latest version has a bug on the `diffClamp` node, so I had to patch the library to make it work. As soon as it's fixed and merged upstream, I'll update the repository to make it expo-friendly, so you will be able to run the example faster.

## Installation

```
yarn install
```

## Running the app

```
yarn start

# iOS
react-native run-ios

# Android
react-native run-android
```
