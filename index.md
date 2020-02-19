Hybrid mobile POS app, based on Ionic 4, Angular 8

![](slides/slide-1.png) ![](slides/slide-2.png) ![](slides/slide-3.png)

## Demo

- [**Android**](POSapp.apk)
- [**Tutorial Video**](https://www.youtube.com/watch?v=mTEK_snO4T8)

## Features

- Manage orders
- Manage menu items
- Customize and printing receipt by Bluetooth (BLE)
- Revenue statistics and reports (comming soon)
- Synchronize data with online account (comming soon)

## Requirements

- NodeJS
- Cordova
- Ionic
- Angular CLI
- Android Studio
- Xcode (to build iOS)

## Build and Run

Open Terminal and go to project root path

### Install dependencies

```
$ npm install
```

### Run on browser

```
$ ionic serve
```

### Run on Android device

```
$ ionic codrova run android
```

### Run on iOS

```
$ ionic cordova prepare ios
```

- Open Xcode. Open project located at `platforms/ios` directory.
- Plug in your iPhone (iPad) into your PC
- Select Build > and select your device to run the app
