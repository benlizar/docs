To run the sample follow these steps:

1) Set the **Allowed Callback URLs** in the [Application Settings](${manage_url}/#/applications/${account.clientId}/settings) so it works for both Android and iOS apps:
```text
auth0.samples.Auth0Samples://${account.namespace}/ios/auth0.samples.Auth0Samples/callback,com.auth0samples://${account.namespace}/android/com.auth0samples/callback
```

2) Set the **Allowed Logout URLs** in the [Application Settings](${manage_url}/#/applications/${account.clientId}/settings) so it works for both Android and iOS apps:
```text
auth0.samples.Auth0Samples://${account.namespace}/ios/auth0.samples.Auth0Samples/callback,com.auth0samples://${account.namespace}/android/com.auth0samples/callback
```

3) Make sure [Node.JS LTS](https://nodejs.org/en/download/) is installed and execute the following commands in the sample's directory:

```bash
npm install # Install dependencies
react-native link react-native-auth0 # Link the native module
react-native run-ios # Run on iOS device
react-native run-android # Run on Android device
```

Read more about how to run react-native apps in their [official documentation](https://facebook.github.io/react-native/docs/running-on-device.html).
