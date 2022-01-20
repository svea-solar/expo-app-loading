# expo-app-loading

This is custom version of expo-app-loading which avoids the splash screen error on ios simulator.

```
[Unhandled promise rejection: Error: No native splash screen registered for given view controller. Call 'SplashScreen.show' for given view controller first.]
```

Our issue

- [SplashScreen warning - Unhandled Promise Rejection](https://github.com/svea-solar/app/issues/2152)

Related github issues

- [[expo-splash-screen] SplashScreen.preventAutoHideAsync() no longer works in iOS](https://github.com/expo/expo/issues/9286)
- [No native splash screen registered for given view controller. ](https://github.com/expo/expo/issues/14749)
- [Expo splash screen gets hidden even if preventAutoHideAsync is used on iOS (not expo or Android)](https://github.com/expo/expo/issues/12481)
- [[expo-splash-screen] No native splash screen registered for given view controller.Call 'SplashScreen.show' for given view controller first](https://github.com/expo/expo/issues/7689)

Once it is fixed in original expo-app-loading, we can stop to use this custom version.

---

[Original readme](https://github.com/expo/expo/tree/master/packages/expo-app-loading)
