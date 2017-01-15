# Readme

## SetUp Dev Enviroment
Clone the git repository:

`git clone git@github.com:kaojo/crash-cook.git`

Prepare npm environment:

`npm run setup`

## Commands Overview

To run the app with live reload in your local browser just type:

`npm run serve`

To run the app with live reload in lab mode in your local browser just type:

`npm run lab`

To run the app with live reload on your phone just type:
Your phone and your computer need to be in the same network

`npm run serve:android`

To deploy your app on your phone just type:

`npm run deploy`

To emulate your app just type:

`npm run emulate`

To start the electron standalone app for dekstop

`npm run electron`

To release all possible products just type:

`npm run release`

Or for android release. Care about the keystore

`npm run release:android`

Or for desktop release. Could take time,

`nom run release:desktop`


`cordova run android (genimotion) / cordova emulate android (android sdk avm)`

Ionic server commands, enter:
  restart or r to restart the client app from the root
  goto or g and a url to have the app navigate to the given url
  consolelogs or c to enable/disable console log output
  serverlogs or s to enable/disable server log output
  quit or q to shutdown the server and exit
  
## Requirements
  
* nodeJs >=7
* npm >= 3
* jdk (oracle)
* android sdk , 24er API
* running Android Virtual Device, eg. Genimotion avd or a avd started via android sdk
* Set your ANDROID_HOME environment variable
* Add Path to Android sdk to PATH variable
