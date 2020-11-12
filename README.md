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
