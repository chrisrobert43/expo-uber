# Uber Clone with Expo

[![made with expo](https://img.shields.io/badge/MADE%20WITH%20EXPO-000.svg?style=for-the-badge&logo=expo&labelColor=4630eb&logoWidth=20)](https://github.com/expo/expo) [![supports iOS and Android](https://img.shields.io/badge/Platforms-Native-4630EB.svg?style=for-the-badge&logo=EXPO&labelColor=000&logoColor=fff)](https://github.com/expo/expo)

[![follow @calebnance](https://img.shields.io/twitter/follow/calebnance.svg?style=for-the-badge&logo=TWITTER&logoColor=FFFFFF&labelColor=00aced&logoWidth=20&color=lightgray)](https://twitter.com/calebnance)

<p align="center">
  <img src="screenshots/screenshare-3.png?raw=true" />
</p>

## Table of Contents

- [Install & Build](#install--build)
- [Stats](#stats)
- [Linting](#linting)
- [Demo & Release Notes](#release-notes)

## Install & Build

Install: `yarn` or `yarn install`

Expo CLI: `npm install -g expo-cli` (if not already installed)

Run Project Locally: `expo start` or `yarn dev`

## Stats

- Expo SDK 35
- React Navigation v3
- PropTypes

## Linting

- `yarn lint`
- prettier and airbnb config
- make sure you have [prettier package](https://atom.io/packages/prettier-atom) installed on your atom/vscode editor
- then make sure to enable these options (packages → prettier):
  - eslint integration
  - stylelint integration
  - automatic format on save (toggle format on save)
- be aware of the `.prettierignore` file

## Release Notes

### version 0.0.1 (current)

- upgraded to [Expo SDK 35](https://blog.expo.io/expo-sdk-35-is-now-available-beee0dfafbf4)
- upgraded to [Expo SDK 34](https://blog.expo.io/expo-sdk-34-is-now-available-4f7825239319)
- upgraded to [Expo SDK 33](https://blog.expo.io/expo-sdk-v33-0-0-is-now-available-52d1c99dfe4c)
- [MapView](https://docs.expo.io/versions/latest/sdk/map-view/) with user's current location ([Expo Location](https://docs.expo.io/versions/v32.0.0/sdk/location/))
- Select Ride Type Modal (Car or Bike & Scooter)
- [Drawer](https://reactnavigation.org/docs/en/drawer-navigator.html) Example with React Navigation

<p align="left">
  <img src="screenshots/screenshot-v0.0.1.jpg?raw=true" width="360" />
</p>
