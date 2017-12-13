# Ziggeo Cordova Demo

This a small sample application on how to use the [Ziggeo API](https://ziggeo.com) for video recording and playback
in Cordova / PhoneGap.


## Setup

Clone the repository on your machine:

```bash
git clone https://github.com/Ziggeo/cordova-ziggeo-demo
```

Install all dependencies:

```bash
npm install
```

Create a file `./ziggeo-credentials.js` with your application token as follows:

```javascript
window.ziggeoApplication = new ZiggeoApi.V2.Application({
    token: "YOUR-APPLICATION-TOKEN"
});
```


## Prepare

Run the following commands to prepare the Cordova application:

```bash
    npm run prepare
    npm run platform add ios
    npm run platform add android
``` 


## Build

Run the following command to build the Cordova application:

```bash
    npm run build
``` 


## Run

Run the following commands to run the Cordova application on iOS / Android:

```bash
    npm run run-ios
    npm run run-android
``` 
