### React Native - Example app to demonstrate integrating React Native into existing native app.


#### Steps to follow


Follow the steps at https://facebook.github.io/react-native/docs/integration-with-existing-apps.html


#### Development


```
git clone git@github.com:cliren/RNIntegration.git
cd RNIntegration
npm install
```

After successfully running the above, open ios project and run.


#### Issues

Currently using the following combination but tried a different versions
 of React Native +0.42 and still get the same error.

```

"react": "15.4.1",
"react-native": "0.42.3"
    
```

**Error:**

```
RNIntegration/js/node_modules/react-native/React/Modules/RCTDevSettings.mm:16:9: fatal error: 'jschelpers/JavaScriptCore.h' file not found
#import <jschelpers/JavaScriptCore.h>
        ^
1 error generated.

```