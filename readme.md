# Example use of react-native-svg and d3 working on react-native ios/android 

Recreated the d3js [Bar Chart](https://bl.ocks.org/mbostock/3885304) using react-native-svg and d3js.

d3js has lots of dom helpers which rely on the dom document so it is difficult to take the bl.ocks.org examples for react-native.

Thanks to [Wolff](http://hswolff.com/blog/react-native-art-and-d3/) I managed to get it working.

## Prerequisites 

https://facebook.github.io/react-native/docs/getting-started.html

## Setup

git clone https://github.com/legg/react-native-svg-d3-example-bar-chart.git
cd react-native-svg-d3-example-bar-chart/
npm i

For Android
react-native run-android

For iOS
react-native run-ios

## common issues

For this error INSTALL_FAILED_UPDATE_INCOMPATIBLE
adb uninstall com.d3native

For EPERM issues
remove android/app/build directory  

