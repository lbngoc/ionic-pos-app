Hybrid mobile POS app, based on Ionic 4, Angular 8

![](assets/img/screen-order.gif) ![](assets/img/screen-food.gif) ![](assets/img/screen-report.png) ![](assets/img/screen-setting.gif)

## Demo

- [**Android**](assets/Ionic-PoS-App.apk)
- [**Tutorial Video**](https://www.youtube.com/watch?v=mTEK_snO4T8)

## Features

- Manage orders **(Listview & Grid View)**
- Manage menu items
- Customize and printing receipt by Bluetooth (BLE). **Support all ESCPOS printers.**
- Revenue statistics and reports **(Completed: since v1.3.1)**
- Synchronize data with online account _(comming soon)_

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
