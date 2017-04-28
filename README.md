# InteReact
React-Native Integration With Existing Apps For Android

1.in your Android project root directory, make a new directory ‘android'
2.copy all android project files into the new 'android' directory
3.in terminal Android project root ,
follow react guide
http://facebook.github.io/react-native/docs/integration-with-existing-apps.html

4.resolve build error
replace
compile "com.facebook.react:react-native:+" // From node_modules.
with
  compile 'com.facebook.react:react-native:0.43.4'
  
  the "0.43.4" is from 

node_module/react-native/android/com/facebook/react-native/0.43.4

