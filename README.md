# Hosting Expo `First-project` on Github Pages Example
 
1. [up-and-running](https://docs.expo.io/versions/v31.0.0/guides/up-and-running.html)

2. Read [hosting-your-app](https://docs.expo.io/versions/v31.0.0/distribution/hosting-your-app) carefully
```
    cd First-project
    expo export --public-url https://ExpoExample.github.io/first-project/
    cd ../ExpoExample.github.io
    cp -r ../first-project/dist first-project
```
3. iOS ![iOS QR](https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=exps://expoexample.github.io/first-project/ios-index.json)
Android ![Android QR](https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=exps://expoexample.github.io/first-project/android-index.json)
