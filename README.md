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
![Landing Screen](Screenshots/Landing_Page.png)
![Login Screen](Screenshots/Login.png)
![Home Screen](Screenshots/Home_Screen.png)
![AD Details Screen](Screenshots/AD_Details.png)
![Sell Car Screen](Screenshots/Sell_car.png)
![Featured Video Screen](Screenshots/Featured_Video_Screen.png)


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
