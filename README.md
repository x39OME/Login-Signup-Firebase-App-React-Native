# Log in Sign up Firebase Authentication React Native

## What did we use in the project?
### 1- [React Native Expo](https://reactnative.dev/)
### 2- [NativeWind](https://www.nativewind.dev/)
### 3- [React Navigation](https://reactnavigation.org/)
### 4- [npm react-native-heroicons](https://www.npmjs.com/package/react-native-heroicons)
### 5- [npm install firebase](https://firebase.google.com/)

## Packages
- npx create-expo-app Login-Signup-Ui
- npm i nativewind
- npm i --dev tailwindcss@3.3.2
- npx tailwindcss init
- npm install @react-navigation/native
- npx expo install react-native-screens react-native-safe-area-context
- npm install @react-navigation/native-stack
- npm i react-native-responsive-screen
- npm i react-native-heroicons
- npm i react-native-heroicons react-native-svg
- npm install firebase
- npx expo install --fix
- npx expo install
- expo install --fix
```
// tailwind.config.js
module.exports = {
- content: [],
+ content: ["./App.{js,jsx,ts,tsx}", "./<custom directory>/**/*.{js,jsx,ts,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
}

  content: [
    "./App.{js,jsx,ts,tsx}", 
    "./screens/**/*.{js,jsx,ts,tsx}",
    "./components/**/*.{js,jsx,ts,tsx}"
  ],

3. Add the Babel plugin

Modify your babel.config.js

// babel.config.js
module.exports = function (api) {
  api.cache(true);
  return {
    presets: ["babel-preset-expo"],
+   plugins: ["nativewind/babel"],
  };
};
```

## Preview Final Project

#### Welcome Screen

<img src="./preview/welcomescreen.jpg" style="width:300px;" alt="Welcome" />

#### Login Screen

<img src="./preview/loginscreen.jpg" style="width:300px;" alt="Login" />

#### Sign up Screen

<img src="./preview/signupscreen.jpg" style="width:300px;" alt="Signup" />

#### Home Screen

<img src="./preview/homescreen.jpg" style="width:300px;" alt="Home" />


## Run The Project
- Download
- Open The Project
- Terminal
- npm i
- npx expo
- -w or Open Expo App On your Phone
