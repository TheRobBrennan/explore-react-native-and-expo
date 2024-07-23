# Welcome

This project explores developing React Native apps using [Expo](https://expo.dev/)

## Quick start

To create a new app using the Expo CLI:

```sh
% npx create-expo-app@latest
✔ What is your app named? … my-app
✔ Downloaded and extracted project files.
> npm install
✅ Your project is ready!

To run your project, navigate to the directory and run one of the following npm commands.

- cd my-app
- npm run android
- npm run ios
- npm run web
```

Once you have your app created, let's start it up with:

```sh
# Start the Metro Bundler to build our app
% npm start
> my-app@1.0.0 start
> expo start

Starting project at /Users/rob/repos/explore-react-native-and-expo/my-app
Starting Metro Bundler
▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄
█ ▄▄▄▄▄ █ ██▀▀█▀▄██ ▄▄▄▄▄ █
█ █   █ █  ▀█ ▀█▄▄█ █   █ █
█ █▄▄▄█ █▀  █▄▀▀▄██ █▄▄▄█ █
█▄▄▄▄▄▄▄█▄█ ▀▄█▄█▄█▄▄▄▄▄▄▄█
█▄▄██ ▄▄▀██▄█▄▀▄ ███ ▀▄▄ ▄█
█▀██   ▄██ ▄█▀██  ▀ █▄  ▀██
█  ▀ ▀▀▄▀ █▀▄▀█▄▀▄▀▄▀▀▄ ▀██
████▄█▀▄ █▄▀ ▄██▄▄▄█▄▀ ▀███
█▄▄▄█▄█▄▄  ▄█▄▀▄▄ ▄▄▄ ▀ ▄▄█
█ ▄▄▄▄▄ █▀▀ █▀█▀▀ █▄█ ▀▀▀▀█
█ █   █ █▄▄▀▄▀▄ █▄▄ ▄▄▀   █
█ █▄▄▄█ █▀▄▀ ▄ ▄▄██▄▀█▀▀ ██
█▄▄▄▄▄▄▄█▄█▄█▄▄█████▄▄▄▄▄▄█

› Metro waiting on exp://192.168.0.8:8081
› Scan the QR code above with Expo Go (Android) or the Camera app (iOS)

› Web is waiting on http://localhost:8081

› Using Expo Go
› Press s │ switch to development build

› Press a │ open Android
› Press i │ open iOS simulator
› Press w │ open web

› Press j │ open debugger
› Press r │ reload app
› Press m │ toggle menu
› Press o │ open project code in your editor

› Press ? │ show all commands

Logs for your project will appear below. Press Ctrl+C to exit.
Recrawled this watch 27 times, most recently because:
MustScanSubDirs UserDroppedTo resolve, please review the information on
https://facebook.github.io/watchman/docs/troubleshooting.html#recrawl
To clear this warning, run:
`watchman watch-del '/Users/rob/repos/explore-react-native-and-expo' ; watchman watch-project '/Users/rob/repos/explore-react-native-and-expo'`
```

Once you see a QR code, you should be able to scan that to run the app on your device.

Alternatively, if you have the iOS simulator or Android simulator installed on your development machine, you can press `i` or `a` to launch your app there.
