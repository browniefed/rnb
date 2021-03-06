# Why React Native

## Reasonings

### Alternatives

There are a lot of alternatives to React Native, including PhoneGap, NativeScript, Titanium Appcelerator, and many others. One of the major benefits of React Native is the concept of "Learn once write anywhere". Once you learn how to build with React you build things the same way with React Native.

### Community

The community for React Native is extremely active. The list of contributors to the React Native core that don't work at Facebook is ever growing. With the ability to bridge Native Views, and Native APIs developers have extended React Natives capabilities beyond what is in the core.

### Stable, Tested, and Production Ready

Although Android has yet to be released it is in active development and already in production for the Facebook Ads Manager on Android. Another great reason to select React Native is because Facebook doesn't release something to the open source world unless they've thoroughly tested it in production.

### Code Reuse

Code reuse is a major aspect of React Native. Code reuse across for both IOS and Android allows you to more easily maintain your applications without hiring multiple teams of developers. Facebook built both the IOS and Android Facebook Ads Manager apps in React Native. They accomplished *87% code resuse* from the IOS app when building the Android app.

### Instant Reload

Instant reload! If you are coming from the native app development world, compiling and rebuilding your app can cost a tremendous amount of time. React Native adopts the web concept that a simple refresh should be all that is needed to get your app to the latest state.

React Native delivers on this promise. With a constant file watcher it will re-build your application and deliver it to wherever your application is running (on device or on the simulator).

### Debugging 

Debugging your application is exactly like you would do it on the web. React Native generally runs your JavaScript in the IOS JavaScript Core however it gives the option to run the JavaScript in Chrome, or in Safari. What that means is you can debug with the Chrome/Safari Dev tools. Use debugger, break points, console.log, and any other techniques you would use on the web.

In a later chapter we will go in depth with Debugging.

### Truly Native

Well the UI is native, the logic in JavaScript. However the benefits of React Native are that the interface that is constructed in JavaScript actually renders to Native components. This gives you the power of actually Native feeling components because you're actually creating Native components. When you use something like PhoneGap and attempt to recreate what a Native component looks and feels like it will generally end in failure. You won't be able to capture all the nuances consistently, and when those native component interactions change you need to rework your components.

So being truly native lets us take advantage actual operating system components, and animations.

## Conclusion

Ultimately it boils down to an active community, code reuse across platforms, debugging, instant reloading, actually being native, and using the same knowledge base to build both web and mobile applications.