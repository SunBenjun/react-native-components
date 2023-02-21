
# react-native-components

## Getting started

`$ npm install react-native-components --save`

### Mostly automatic installation

`$ react-native link react-native-components`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-components` and add `RNComponents.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNComponents.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.kll.components.RNComponentsPackage;` to the imports at the top of the file
  - Add `new RNComponentsPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-components'
  	project(':react-native-components').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-components/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-components')
  	```


## Usage
```javascript
import RNComponents from 'react-native-components';

// TODO: What to do with the module?
RNComponents;
```
  