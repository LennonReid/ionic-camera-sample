Run the App​
# Run the App​
```bash
ionic serve
```

# Deploying to iOS and Android


```bash
ionic build
```

Next, create both the iOS and Android projects:

```bash
$ ionic cap add ios
$ ionic cap add android
```
Every time you perform a build (e.g. ionic build) that updates your web directory (default: www), you'll need to copy those changes into your native projects:

```bash
ionic cap copy
```

## iOS Deployment​
```bash
ionic cap open ios
```

Follow the [tutorial](https://ionicframework.com/docs/angular/your-first-app/deploying-mobile) 
