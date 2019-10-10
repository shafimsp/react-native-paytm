# react-native-paytm

## Getting started

`$ npm install react-native-paytm --save`

### Mostly automatic installation

`$ react-native link react-native-paytm`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-paytm` and add `RNPayTm.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNPayTm.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.shafimsp.paytm.RNPayTmPackage;` to the imports at the top of the file
  - Add `new RNPayTmPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-paytm'
  	project(':react-native-paytm').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-paytm/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-paytm')
  	```


## Usage
```javascript
import RNPayTm from 'react-native-paytm';

// TODO: What to do with the module?
RNPayTm;
```
