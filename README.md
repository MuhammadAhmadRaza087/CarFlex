This is a new [**React Native**](https://reactnative.dev) project, bootstrapped using [`@react-native-community/cli`](https://github.com/react-native-community/cli).

# Getting Started

>**Note**: Make sure you have completed the [React Native - Environment Setup](https://reactnative.dev/docs/environment-setup) instructions till "Creating a new application" step, before proceeding.

## Step 1: Start the Metro Server

First, you will need to start **Metro**, the JavaScript _bundler_ that ships _with_ React Native.

To start Metro, run the following command from the _root_ of your React Native project:

```bash
# using npm
npm start

# OR using Yarn
yarn start
```

## Step 2: Start your Application

Let Metro Bundler run in its _own_ terminal. Open a _new_ terminal from the _root_ of your React Native project. Run the following command to start your _Android_ or _iOS_ app:

### For Android

```bash
# using npm
npm run android

# OR using Yarn
yarn android
```

### For iOS

```bash
# using npm
npm run ios

# OR using Yarn
yarn ios
```

If everything is set up _correctly_, you should see your new app running in your _Android Emulator_ or _iOS Simulator_ shortly provided you have set up your emulator/simulator correctly.

This is one way to run your app — you can also run it directly from within Android Studio and Xcode respectively.

## Step 3: Modifying your App

Now that you have successfully run the app, let's modify it.

1. Open `App.tsx` in your text editor of choice and edit some lines.
2. For **Android**: Press the <kbd>R</kbd> key twice or select **"Reload"** from the **Developer Menu** (<kbd>Ctrl</kbd> + <kbd>M</kbd> (on Window and Linux) or <kbd>Cmd ⌘</kbd> + <kbd>M</kbd> (on macOS)) to see your changes!

   For **iOS**: Hit <kbd>Cmd ⌘</kbd> + <kbd>R</kbd> in your iOS Simulator to reload the app and see your changes!

## Congratulations! :tada:

You've successfully run and modified your React Native App. :partying_face:

### Now what?

- If you want to add this new React Native code to an existing application, check out the [Integration guide](https://reactnative.dev/docs/integration-with-existing-apps).
- If you're curious to learn more about React Native, check out the [Introduction to React Native](https://reactnative.dev/docs/getting-started).

# Troubleshooting

If you can't get this to work, see the [Troubleshooting](https://reactnative.dev/docs/troubleshooting) page.

# Learn More

To learn more about React Native, take a look at the following resources:

- [React Native Website](https://reactnative.dev) - learn more about React Native.
- [Getting Started](https://reactnative.dev/docs/environment-setup) - an **overview** of React Native and how setup your environment.
- [Learn the Basics](https://reactnative.dev/docs/getting-started) - a **guided tour** of the React Native **basics**.
- [Blog](https://reactnative.dev/blog) - read the latest official React Native **Blog** posts.
- [`@facebook/react-native`](https://github.com/facebook/react-native) - the Open Source; GitHub **repository** for React Native.
# CarFlex
Certainly! Below is a sample README file that you can use as a starting point for your project on GitHub. Please note that you may need to customize it further based on your project's specific details.

---

# CarFlex App

CarFlex is a mobile application built using React Native for car enthusiasts. It allows users to explore car videos, manage their profiles, and more.

## Table of Contents
- [Features](#features)
- [Screenshots](#screenshots)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Welcome Screen:** A welcome screen that allows users to sign in with Facebook, Google, or credentials.
- **Profile Management:** Users can view and edit their profiles, including name, email, phone number, gender, and profile picture.
- **Video Exploration:** Users can explore featured and other car-related videos.
- **Sign-Up:** New users can create an account by providing their name, email, and password.
- **Login:** Existing users can log in using their credentials.

## Screenshots
You can visit Figma to see it's frontend design. The link: https://www.figma.com/file/VJzIKtEFXm8tW8Iq7wAQtd/Car-Flex-Interface?type=design&node-id=0%3A1&mode=design&t=P5b5cN4OyDNUGQiz-1

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)

### Installation
1. Clone the repository.
   ```bash
   git clone https://github.com/yourusername/CarFlex.git
   cd CarFlex
   ```
2. Install dependencies.
   ```bash
   npm install
   ```
   or
   ```bash
   yarn install
   ```

## Usage
1. Run the application.
   ```bash
   npx react-native run-android
   ```
   or
   ```bash
   npx react-native run-ios
   ```
2. Explore the app on your emulator or connected device.

## Project Structure
- `src`: Contains the source code for the React Native app.
  - `components`: Reusable components used across screens.
  - `screens`: Individual screens of the application.
  - `navigation`: Navigation configuration.
  - `context`: Context providers.

## Technologies Used
- React Native
- Firebase (Authentication, Firestore)
- Fetch API (Rapid API)

## Contributing
Contributions are welcome! Fork the repository and submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
