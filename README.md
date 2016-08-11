# webRTC-cordova-samples
WebRTC samples inside cordova and crosswalk

Based on: https://webrtc.github.io/samples/

Using less plugins as posible.

Disclaimer:  I COMMIT ALL

Creation steps (OSX):

1) Cordova HelloWorld

```sh
$ sudo npm install -g cordova
$ cordova create hello com.example.hello HelloWorld
$ cd hello
$ cordova platform add android --save
```

2) Install crosswalk plugin this process add preferences in config.xml 

IMPORTANT: Change the cordova-plugin in order to change the crosswalk version. 

| cordova-plugin v. | crosswalk v. |
| ------------- |:-------------:|
| cordova-plugin-crosswalk-webview@1.8.0 | 19 |
| cordova-plugin-crosswalk-webview@1.7.0 | 18 |
| cordova-plugin-crosswalk-webview@1.6.0 | 17 |
| cordova-plugin-crosswalk-webview@1.5.0 | 16 |

Go install lastest

```sh
$ cordova plugin add cordova-plugin-crosswalk-webview
$ cordova build
$ cordova run android
```


3) Install cordova-plugin-whitelist
and set config.xml (check comits)
```sh
$ cordova plugin add cordova-plugin-whitelist
```