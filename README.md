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
|  https://www.npmjs.com/package/react-native-splash-screen | Splash screen  |
|  https://www.npmjs.com/package/react-native-appearance | Appearance, color scheme  |




### React Native useful links
| Link | Description |
| ------ | ------ |
|  https://github.com/vhpoet/react-native-styling-cheat-sheet | Styling cheat sheet  |
|  https://www.awesome-react-native.com/ | Awesome react native  |
| http://www.reactnative.com/ |
|  https://reactnativemaster.com/  |
| https://reactnativeexample.com/ |
| https://reactnative.directory/ |
| https://www.reactnative.express/ |
| https://aboutreact.com/ |
| https://blog.logrocket.com/building-a-splash-screen-in-react-native/ | Splash screen |
| https://github.com/ReactNativeNews/React-Native-Apps | App built with React Native source codes  |




### React Native UI Library/Framework
| Link | Description |
| ------ | ------ |
|  https://github.com/rilyu/teaset | teaset  |
|  https://github.com/wix/react-native-ui-lib | ui lib  |
|  https://reactnativeelements.com/ | React native element, components library  |
|  https://akveo.github.io/react-native-ui-kitten/ | kitten  |


 ## Install React Native
 
 ```
 npm i -g react-native
 
npm i -g react-native-cli

npx react-native init <FolderName>
```


 ## Install Java in Ubuntu
https://www.digitalocean.com/community/tutorials/how-to-install-java-with-apt-on-ubuntu-18-04

https://linuxize.com/post/install-java-on-ubuntu-18-04/ 

to install java on ubuntu
 ```
sudo apt update

sudo apt install default-jdk

sudo apt install default-jre
```
To check installed java version
 ```
java -version

javac -version
```
 ## Add SDK location to run the app
 
  [Stack overflow answer](https://stackoverflow.com/a/43626724/3882241)


When running others project or cloned project from github, to run it on android use the same
 

Go to your React-native Project -> Android

Create a file __local.properties__ 

Open the file

paste your Android SDK path like below


in Windows sdk.dir = C:\\Users\\USERNAME\\AppData\\Local\\Android\\sdk

in macOS sdk.dir = /Users/USERNAME/Library/Android/sdk

in linux sdk.dir = /home/USERNAME/Android/Sdk

Replace USERNAME with your user name


Now, Run the react-native run-android in your terminal.

example in my system sample file is

__sdk.dir = /home/user5/Android/Sdk__ 





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

 ## React native Link
 react-native link is an automatic way for installing native dependencies. It is an alternative to manually linking the dependency in your project. 
 
 [Stack overflow answer](https://stackoverflow.com/a/54764060/3882241)
 ```
npm i -g react-native-cli
```

[RN1]: <https://www.youtube.com/playlist?list=PLYxzS__5yYQmdfEyKDrlG5E0F0u7_iIUo>
