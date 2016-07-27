# 7th FCSIT Hybrid Mobile Application

## Description
Hybrid Mobile Application with Wordpress back-end based on https://github.com/shprink/wordpress-hybrid-client

## Quick Start

### Prerequisites

- Git
- NodeJS (recommended: 4.x), please do not use npm 5.x for now
- NPM (recommended: 3.3.x)

This installation works on both OSX and Linux. Windows is not supported yet,

# Run on the browser
$ npm run devserver
```

Open http://localhost:8080/webpack-dev-server/ in Chrome (the only browser supported). You should see the application running with `http://fcsitsymposium.esy.es/wp-json` backend.

To go further please read the documentations.

## Project public API

```
# Dev server
npm run devserver

# Dump files in www
npm run dumpdev
npm run dumpprod

# Run Cordova
npm run android
npm run ios
npm run iosEmulator

# Cordova build
npm run buildAndroid
npm run buildProdAndroid
npm run buildIOS
npm run buildProdIOS
```