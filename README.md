# webRTC-cordova-samples
WebRTC samples inside cordova and crosswalk

Based on: https://webrtc.github.io/samples/

Creation steps:

1) Cordova HelloWorld

```sh
$ sudo npm install -g cordova
$ cordova create hello com.example.hello HelloWorld
$ cd hello
```
2) Install crosswalk plugin before de add cordova platform
```sh
$ cordova plugin add cordova-plugin-crosswalk-webview
$ cordova platform add android --save
$ cordova build
$ cordova run android
```