# React Native Web Starter

## Introduction

#### Navigation is done using react router so look up docs for that and the repo credited at the bottom of the README contains information about how it works for mobile. I've aliased the `<Navigation />` component to `<Switch />` and `<Card />` to `<Route />` to make the lib more platform agnostic

This repo is intending to provide an easy starting point for developers looking to make fully cross platform applications across both web with [React Native Web](https://github.com/necolas/react-native-web) and mobile with [Expo](https://github.com/react-community/create-react-native-app).

It is bootstrapped with [Create React App](https://github.com/facebook/create-react-app) so you can run `yarn web` in order to start up the development web server with all the hot reloading goodness you've come to expect.

It has then been integrated with [Create React Native App](https://github.com/react-community/create-react-native-app) and running `yarn ios` or `yarn android` will start the Expo packager. You can also run the project from the Expo XDE program.

## Get Started
Clone the branch with the starting point you want and just rename the project (don't forget the `package.json`, Run `git remote rm origin && yarn` to remove the ref to this repo and install node_modules then you're good to go. 🙂

A full list of the scripts defined in `package.json` is shown below.

| Script              | Action                                                  |
|---------------------|---------------------------------------------------------|
| `yarn web`          | Start CRA Development Build                             |
| `yarn build-web`    | Create production build for web                         |
| `yarn eject-web`    | Eject from CRA                                          |
| `yarn start-native` | Start the Expo packager                                 |
| `yarn eject-native` | Eject from Expo                                         |
| `yarn android`      | Start expo packager and install app to Android Emulator |
| `yarn ios`          | Start expo packager and install app to iOS Simulator    |
| `yarn test-native`  | Run testing script for mobile app                       |
| `yarn test-web`     | Run testing script for web app                          |
| `yarn test`         | Run both testing scripts                                |

### Credit

- Huge thanks to [Nicolas Gallagher](https://github.com/necolas) for making React Native Web
- Thanks to [Expo](https://expo.io/) for making it so easy to get started with React Native development
- Thanks to [Yannick Spark](https://twitter.com/yannickdot) for writing [this great article](https://medium.com/@yannickdot/write-once-run-anywhere-with-create-react-native-app-and-react-native-web-ad40db63eed0) which inspired me to get started with React Native Web
- Thanks to [Léo Le Bras](https://github.com/LeoLeBras) for writing the [React Router Navigation](https://github.com/LeoLeBras/react-router-navigation) library that I've used for this branch
