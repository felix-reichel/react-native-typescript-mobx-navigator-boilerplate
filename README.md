# Installation
## System - Requirements:
Aktueller Versionen von:
- Node v6.11.x
- Npm 5.x.x
- Carthage 0.25.x

-> npm install (uses dependecies from npm-shrinkwrap.json)  
-> cd node_modules/react-native-ble-plx/BleClientManager && carthage update  
-> npm run start:ios oder npm run start:android  
bzw.   
    "start:ios": "npm run build && concurrently -r 'npm run watch' 'react-native run-ios'",  
    "start:android": "npm run build && concurrently -r 'npm run watch' 'react-native run-android'",  

# Changelog
## 2. Oktober 2017
### > Inits react-native, typescript, jest, mobx, mobx-react, react-native-ble-plx
