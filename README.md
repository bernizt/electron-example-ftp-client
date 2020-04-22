# FTP Client Electron Example

An Electron example built using [electron-webpack](https://webpack.electron.build/) with TypeScript support. [Icon by Dryicons](https://dryicons.com/free-icons/file-types-icons). No JavaScript Framework used.

This repository is simply an Electron example and should be treated as such.

Features:
- List files from an FTP directory
- Upload a file to an FTP directory by dropping it into the application window

This example was accompanied by a quick introdution to Electron presentation, which can be found [here](https://slides.com/bernatzaragozatravieso/electronintro).

## Scripts

Run and compile the example with the following scripts (same as [electron-webpack-quick-start](https://github.com/electron-userland/electron-webpack-quick-start)). An FTP server command is also available for testing purposes.

```bash
# run application in development mode
yarn dev

# compile source code and create webpack output
yarn compile

# `yarn compile` & create build with electron-builder
yarn dist

# `yarn compile` & create unpacked build with electron-builder
yarn dist:dir

# serve the project directory via FTP, for testing purposes
yarn ftp-srv
```
