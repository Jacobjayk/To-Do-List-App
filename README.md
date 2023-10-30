# To-do List App

To-do list App is a simple and elegant app that helps you organize your tasks and projects. You can create lists, add tasks, mark them as done, and delete them. You can also sync your data with Firebase and access your tasks from any device. The app is built with React Native, Expo, and Firebase.

## Table of Content:

- [About The App](#about-the-app)
- [Screenshots](#screenshots)
- [Technologies](#technologies)
- [Setup](#setup)
- [Approach](#approach)
- [Status](#status)

## About The App

This app is a simple to-do app that allows you to create a list of tasks you need to complete. It also has quote feature that gives you a quote to motivate you. It is built with react-native, redux, firebase and expo.

## Screenshots

<p align="center">
 <img width=200 src="https://github.com/Jacobjayk/To-Do-List-App/assets/98883398/d791a900-02d4-44f6-82c2-c9e8d56d16fe" />
 <img width=200 src="https://github.com/Jacobjayk/To-Do-List-App/assets/98883398/23eb14ce-17f8-4f3b-9b69-c7ca73fb6849" />
 <img width=200 src="https://github.com/Jacobjayk/To-Do-List-App/assets/98883398/1cd8f888-d2a0-4484-b414-781aefac2126" />
 <img width=200 src="https://github.com/Jacobjayk/To-Do-List-App/assets/98883398/bd5f6578-4088-40a4-b863-bcbe5216b07f" />
</p>

## Technologies

- [React Native](https://reactnative.dev/)
- [Redux](https://redux.js.org/)
- [Firebase](https://firebase.google.com/)
- [Expo](https://expo.io/)
- [React Navigation](https://reactnavigation.org/)

## Setup

- download or clone the repository
- run `npm install` to install all the dependencies
- create a firebase project and add the firebase config to the `firebase/index.js` file
- set up the firebase database, enable email authentication and add the rules to the database
- run `npm run start` or `npm run android` or `npm run ios` to start the app

#### firestore structure:

```
{
  "users": {
    "user_id": {
      "todos": [
        {
          "id": "todo_id",
          "text": "todo_title",
          "description": "todo_description",
          "completed": false
        }
      ]
    }
  }
}
```

## Approach

- I started by creating the app with expo and react-native
- added redux to the app
- added firebase to the app
- added the login feature to the app
- added the logout feature to the app
- added the todo feature to the app
- added the quote feature to the app
- added react-navigation to the app

## Status

# This app is my first react-native app. It is a sample app that I built to learn react-native.

=======

# To-do List App

To-do list App is a simple and elegant app that helps you organize your tasks and projects. You can create lists, add tasks, mark them as done, and delete them. You can also sync your data with Firebase and access your tasks from any device. The app is built with React Native, Expo, and Firebase.

## Table of Content:

- [About The App](#about-the-app)
- [Screenshots](#screenshots)
- [Technologies](#technologies)
- [Setup](#setup)
- [Approach](#approach)
- [Status](#status)

## About The App

This app is a simple to-do app that allows you to create a list of tasks you need to complete. It also has quote feature that gives you a quote to motivate you. It is built with react-native, redux, firebase and expo.

## Screenshots

<p align="center">
 <img width=200 src="https://github.com/Jacobjayk/To-Do-List-App/assets/98883398/d791a900-02d4-44f6-82c2-c9e8d56d16fe" />
 <img width=200 src="https://github.com/Jacobjayk/To-Do-List-App/assets/98883398/23eb14ce-17f8-4f3b-9b69-c7ca73fb6849" />
 <img width=200 src="https://github.com/Jacobjayk/To-Do-List-App/assets/98883398/1cd8f888-d2a0-4484-b414-781aefac2126" />
 <img width=200 src="https://github.com/Jacobjayk/To-Do-List-App/assets/98883398/bd5f6578-4088-40a4-b863-bcbe5216b07f" />
</p>

## Technologies

- [React Native](https://reactnative.dev/)
- [Redux](https://redux.js.org/)
- [Firebase](https://firebase.google.com/)
- [Expo](https://expo.io/)
- [React Navigation](https://reactnavigation.org/)

## Setup

- download or clone the repository
- run `npm install` to install all the dependencies
- create a firebase project and add the firebase config to the `firebase/index.js` file
- set up the firebase database, enable email authentication and add the rules to the database
- run `npm run start` or `npm run android` or `npm run ios` to start the app

#### firestore structure:

```
{
  "users": {
    "user_id": {
      "todos": [
        {
          "id": "todo_id",
          "text": "todo_title",
          "description": "todo_description",
          "completed": false
        }
      ]
    }
  }
}
```

## Approach

- I started by creating the app with expo and react-native
- added redux to the app
- added firebase to the app
- added the login feature to the app
- added the logout feature to the app
- added the todo feature to the app
- added the quote feature to the app
- added react-navigation to the app

## Status

This app is my first react-native app. It is a sample app that I built to learn react-native.
