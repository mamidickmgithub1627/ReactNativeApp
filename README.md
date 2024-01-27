# ReactNativeApp

 Follow the Instructions from the following document under the section react native CLI to set up the environment in Android Studio
 https://reactnative.dev/docs/environment-setup

Once created a dummy project as above mentioned in documents, verify the set up using `npm react-native doctor` command.
Prefer Android device over android emulator to avoid any errors.
Once environment set up is done, run the following command.
`npm start` to execute.
The terminal will ask options , type a for android.

command for bundle te assets `npx react-native bundle --platform android --dev false --entry-file index.js --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest <PATH>`


