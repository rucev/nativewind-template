# React Native (JS) + Expo + NativeWind Basic Template

This repository provides a clean and minimal template for developing React Native (RN) applications using NativeWind. 

I created this template to serve as a reliable starting point, after almost always encountering issues when setting up NativeWind in a new RN project (whether following the official documentation or various online tutorials).

## How to Use

### Download the Code
Fork, Clone the repository or download the ZIP file.

```sh
cd app
```

### Install Dependencies

```sh
npm install
```

### Run in Development Mode

```sh
npm run start
```

### Check the App

You can preview the app using the [Expo Go](https://expo.dev/go) app on your mobile device or run it on an Android/iOS emulator on your computer.

To verify that everything is working correctly, try modifying the `red` Tailwind class in `App.js` to `blue`—the background color should change accordingly. Now you’re all set to continue developing your app using NativeWind for styling!

### Build Your App

To build your app, follow the [Expo EAS](https://docs.expo.dev/build/setup/) documentation. You will need to create an `eas.json` file in the root folder of your project and update the `app.json` file with your project ID and name.
