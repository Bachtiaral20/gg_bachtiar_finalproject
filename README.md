# Generasi Gigih Playlist

This is a project for Final Project Generasi Gigih Batch 2 in FrontEnd track [Generasi Gigih](https://www.anakbangsabisa.org/generasi-gigih/program). Spotify API give ability to track down your favorite musics, select them all, and just sit back and relax, then you got playlist of your favorite musics!

## Features

- **Login** using your Spotify Developer account 🔊
- **Create playlist** from your favorite music 🎧
- Take a look on all of your favorite musics by find on **Search music** feature 🔍

## Build using

- [Create React App](https://create-react-app.dev/) to initialize the project.
- [Typescript](https://typescriptlang.org).
- [Jest](https://jestjs.io/), [react testing-library](https://testing-library.com/) for testing the UI and implementation.
- [Material UI](https://mui.com/) and [Emotion](https://emotion.sh/docs/introduction) to make the user interface.
- Deploy using [Vercel](https://vercel.com/).
- [React redux](https://react-redux.js.org/) for state management (store).

## Getting Started

This is the guidance in case you want to run this project on your own

### Run The App

1. Clone this repository
```
git clone https://github.com/Bachtiaral20/gg_bachtiar_finalproject
```
2. Open the project directory folder from your command prompt or Git Bash
```bash
cd gg_bachtiar_finalproject
```
3. Installing the packages
```
npm install
```
4. Setup the [environment variable]() to run this project.
5. Start the server
```
npm start
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result

### Run Test

You can launch the test runner by using
### `npm run test`

## Environment Variable

You have to set the `.env` file to add environment variable to run this project
- Create the `.env` file.
- Update your `.env` 
```
REACT_APP_SPOTIFY_CLIENT_ID = Your client id retrieved from Spotify Developer account
```