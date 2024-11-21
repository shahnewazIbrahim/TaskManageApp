# Task Manager App

A simple and well-designed mobile app for managing tasks, built using **React Native** and **Expo**. This app allows you to add, view, complete, and delete tasks, with data persistence using AsyncStorage.

---

## Features

- **Add New Tasks**: Quickly add tasks with a single tap.
- **Mark Tasks as Completed**: Keep track of your progress by marking tasks as done.
- **Delete Tasks**: Easily remove tasks you no longer need.
- **Persistent Storage**: Your tasks are saved locally on your device using AsyncStorage.
- **User-Friendly Interface**: A clean and intuitive design for ease of use.

---

## Screenshots

*(Add screenshots of your app here after deployment, if available)*

---

## Technologies Used

- **React Native**: For building the mobile app.
- **Expo**: For fast development and testing.
- **AsyncStorage**: To persist data locally on the device.
- **React Native Vector Icons**: For beautiful icons.

---

## Installation and Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/task-manager-app.git
   cd task-manager-app

2. Install dependencies:
   ```bash
    npm install

3. Run the development server:
   ```bash
    npm start



## Building APK

1. Install EAS CLI:
   ```bash
   npm install -g eas-cli

2. Configure the build:
   ```bash
    eas build:configure

3. Build the APK:
   ```bash
    eas build -p android --profile preview

3. Download the APK from the build dashboard link provided by Expo.


## Folder Structure

1. Install EAS CLI:
   ```bash
    .
    ├── App.js                 # Main app component
    ├── assets/                # App assets (images, icons, etc.)
    ├── node_modules/          # Project dependencies
    ├── package.json           # App metadata and dependencies
    ├── eas.json               # EAS build configuration
    ├── README.md              # Documentation (this file)


## Folder Structure

1. Install EAS CLI:
   ```bash
    Add task categories (e.g., Work, Personal, Shopping).
    Implement reminders/notifications for tasks.
    Enable cloud synchronization with Firebase or a custom backend.
    Add a dark mode toggle for better usability.
