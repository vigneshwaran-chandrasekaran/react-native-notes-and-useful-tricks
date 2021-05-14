### React Native tutorials
| Link | Description |
| ------ | ------ |
|  https://www.reactnativeschool.com/ | reactnativeschool  |
|  https://medium.com/@spencer_carli | spencer carli  |
|  http://www.reactnativeexpress.com/ | reactnativeexpress by https://www.newline.co/fullstack-react-native/#  |


### React Native video tutorials
| Link | Description |
| ------ | ------ |
|  https://www.youtube.com/c/HandlebarLabs/videos | HandlebarLabs by reactnativeschool |
|  https://www.youtube.com/c/wcandillon/videos | William Candillon |
|  [React Native Animation][RN1] |



### React Native Tools
| Link | Description |
| ------ | ------ |
|  https://appetize.io/ | Native mobile apps in browser  |

### React Native useful packages
| Link | Description |
| ------ | ------ |
|  https://github.com/react-native-training/react-native-fonts | React native fonts  |
|  https://reactnativeelements.com/ | React native element, components library  |
|  https://www.npmjs.com/package/react-native-splash-screen | Splash screen  |
|  https://www.npmjs.com/package/react-native-appearance | Appearance, color scheme  |




### React Native useful links
| Link | Description |
| ------ | ------ |
|  https://github.com/vhpoet/react-native-styling-cheat-sheet | Styling cheat sheet  |
|  https://www.awesome-react-native.com/ | Awesome react native  |
|  https://reactnativemaster.com/  |
| https://reactnativeexample.com/ |
| https://reactnative.directory/ |
| https://aboutreact.com/ |
| https://blog.logrocket.com/building-a-splash-screen-in-react-native/ | Splash screen |
| https://github.com/ReactNativeNews/React-Native-Apps | App built with React Native source codes  |




### React Native UI Library/Framework
| Link | Description |
| ------ | ------ |
|  https://github.com/rilyu/teaset | teaset  |
|  https://github.com/wix/react-native-ui-lib | ui lib  |




 ## Absolute path in React native
 Babel Plugin Module Resolver [Module Resolver](https://github.com/tleunen/babel-plugin-module-resolver)
 
 [Stack overflow answer](https://stackoverflow.com/a/57039921/3882241)
 ```
 npm install --save-dev babel-plugin-module-resolver 
```
Example configuration of babel.config.js:

```
module.exports = {
  ...other config

  plugins: [
    ['module-resolver', {
      root: [
        './src',
      ],
      "alias": {
        "~": "./src",
      }
    }],
  ],
};
```

