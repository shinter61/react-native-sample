## package追加時のおまじない
```
watchman watch-del-all
rm -rf node_modules
yarn
cd ios 
pod cache clean --all
pod install
cd ..
yarn start --reset-cache
```

## Trouble shooting
- Red screen with "Unrecognized font family" error on iOS

https://wp-kyoto.net/react-native-vector-icons-red-screen-with-unrecognized-font-family-error-on-ios/
https://github.com/oblador/react-native-vector-icons#red-screen-with-unrecognized-font-family-error-on-ios
