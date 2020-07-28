![Continuous Integration](https://github.com/saihaj/saihaj-react-native-starter/workflows/Continuous%20Integration/badge.svg)

# Development Setup

This is a `react-native init` project. That has eslint and other add-ons that are preset for my projects.

Soon will also add github actions for deployment.

## Prerequisites
* Follow React Native [docs] to install all the dependencies (https://reactnative.dev/docs/environment-setup)
* Once you get to "Creating New Application". Clone this project.
* Install this project's dependencies
  ```
  npm install
  ```

## ESLint is enabled on this project

## Available Scripts

`npm run <command>`

#### `Commands`
```
start:android   Start the Android emulator
start:ios       Start the iOS emulator
start-sims      Start Android and iOS emulators

clean           react-native-clean-project
clean:android   Clean Android build files
clean:ios       Clean iOS build files

lint            ESLint and checks code style
test            Unit + integration tests in watcher mode

install-assets 	Install any changed files in the "assets/" directory
install-pods    Install all the pods for ios
```

## Helpful

* Rename this project:  [`react-native-rename`](https://www.npmjs.com/package/react-native-rename) makes it easy to change it with just one command.
* Checkout [Fastlane](https://docs.fastlane.tools/getting-started/cross-platform/react-native/) for releasing apps
* Cleans React Native project by purging caches and modules, and reinstalling them again.[`react-native-clean-project`](https://github.com/pmadruga/react-native-clean-project)
## Credits
Eslint configurations and npm scripts are inspired from [@ShabadOS/mobile](https://github.com/ShabadOS/mobile)
