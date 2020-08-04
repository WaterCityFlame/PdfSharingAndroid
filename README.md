# This is a proof of concept of a bug in react-native-share
Sharing PDF files that are base-64 encoded does not work on Android with targetSdk 29, but it does work with targetSDK 28

On the master branch you'll see the broken version, and on target-sdk-28 you'll see the working version. 

This app will just display a pdf (using react-native-pdf) and provide a (broken) share button for that pdf.

## To Download & Run
- Clone the repo
- cd into it
- `npm install`
- `npx react-native run-android`

