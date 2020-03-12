# Video Chat code sample for Cordova for ConnectyCube platform

This README introduces [ConnectyCube](https://connectycube.com) Video Chat code sample for Cordova

Project contains the following features implemented:

- User authorization
- Group video calls (up to 4 users)
- Mute/unmute microphone
- Switch cameras

## Documentation

ConnectyCube Cordova getting started - [https://developers.connectycube.com/cordova](https://developers.connectycube.com/cordova)

ConnectyCube Video Chat API documentation - [https://developers.connectycube.com/cordova/videocalling](https://developers.connectycube.com/cordova/videocalling)

## Screenshots

<kbd><img alt="Cordova video chat code sample, login" src="https://developers.connectycube.com/docs/_images/code_samples/cordova/cordova_codesample_video_login.PNG" width="200" /></kbd> <kbd><img alt="Cordova video chat code sample, select users" src="https://developers.connectycube.com/docs/_images/code_samples/cordova/cordova_codesample_video_select_users.PNG" width="200" /></kbd> <kbd><img alt="Cordova video chat code sample, video chat" src="https://developers.connectycube.com/docs/_images/code_samples/cordova/cordova_codesample_video_video.PNG" width="200" /></kbd>

## Quick start

1. Clone the project;
2. Install node_modules: `cd connectycube-cordova-samples/sample-videochat-cordova && npm install`;
3. Run `cordova clean ios && cordova emulate ios` or `cordova clean android && cordova emulate android`.

## Running on a device

The above command will automatically run your app on the Simulator. If you want to run the app on an actual physical  device, please use the following commands:

* `cordova clean ios && cordova run ios --device`
* `cordova clean android && cordova run android --device`.

## Can't build yourself?

Got troubles with building Cordova code sample? Just create an issue at [Issues page](https://github.com/ConnectyCube/connectycube-ccordova-samples/issues) - we will create the sample for you. For FREE!