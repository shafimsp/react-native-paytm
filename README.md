# react-native-paytm

## Getting started

`$ npm install react-native-rn-pay-tm --save`

### Mostly automatic installation

`$ react-native link react-native-rn-pay-tm`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-rn-pay-tm` and add `RnPayTm.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRnPayTm.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.reactlibrary.RnPayTmPackage;` to the imports at the top of the file
  - Add `new RnPayTmPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-rn-pay-tm'
  	project(':react-native-rn-pay-tm').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-rn-pay-tm/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-rn-pay-tm')
  	```


## Usage
```javascript
import RnPayTm from 'react-native-rn-pay-tm';

// TODO: What to do with the module?
RnPayTm;
```
