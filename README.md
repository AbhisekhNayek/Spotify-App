# React Native Spotify App

![GitHub stars](https://img.shields.io/github/stars/AbhisekhNayek/Spotify-App.svg?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/AbhisekhNayek/Spotify-App.svg?style=flat-square)
![GitHub license](https://img.shields.io/github/license/AbhisekhNayek/Spotify-App.svg?style=flat-square)

A React Native app that allows users to interact with the Spotify API and explore music features.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Features

- Authenticate with Spotify API
- Fetch user's playlists, top tracks, and more
- Play and control music tracks
- Search for artists, albums, and tracks

## Installation

1. Clone the repository:

```bash
git clone https://github.com/AbhisekhNayek/Spotify-App.git
cd your-repo
```

2. Install dependencies:

```bash
npm install
# or
yarn install
```

3. Set up your Spotify API credentials:

   - Visit the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/applications).
   - Create a new app.
   - Copy the `Client ID` and `Client Secret`.
   - Create a `.env` file in the project root and add your credentials:

     ```dotenv
     SPOTIFY_CLIENT_ID=your-client-id
     SPOTIFY_CLIENT_SECRET=your-client-secret
     REDIRECT_URI=your-redirect-uri
     ```

## Usage

1. Start the React Native development server:

```bash
npm start
# or
yarn start
```

2. Run the app on an emulator or device:

```bash
npm run android
# or
npm run ios
```

## Screenshots

Include screenshots or GIFs demonstrating your app's functionality. You can create a folder named `screenshots` or `assets` to store these files.

## Contributing

Feel free to contribute to this project. Follow the [contribution guidelines](CONTRIBUTING.md) for more details.

## License

This project is licensed under the [MIT License](LICENSE).
