# reanimated-collapsible-navbar

Small demo to show how to implement a collapsible navigation bar in React Native, with all the animations running on the UI thread and without the JS thread having to intervene. The GIF below showcases how the JS thread is intentionally frozen and still the snapping animation gets executed after the gesture release.

## Expo
The application is available in Expo ready to play with: https://expo.io/@rgommezz/reanimated-collapsible-navbar

## Running the app locally
You need to have `expo-cli` installed locally. After cloning the repo execute:

```bash
yarn install
expo start
```

## Article explaining the code
https://medium.com/@rgommezz/reanimating-your-react-native-experience-d1377d51118a

![collapsiblenavbar3](https://user-images.githubusercontent.com/4982414/43739544-c16401fa-99c8-11e8-8f3c-0ef1da21ac6e.gif)
