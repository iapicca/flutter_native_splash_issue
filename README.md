### DESCRIPTION

Running application shows warning 
```console
WARNING: found an existing <meta name="viewport"> tag. Flutter Web uses its own viewport configuration for better compatibility with Flutter. This tag will be replaced.
```

### STEP TO REPRODUCE

- create app running `flutter create flutter_native_splash_issue`
- add `flutter_native_splash` to the dependencies
- add `splashscreen.yaml` file to the project
- create splash screen running `flutter pub run flutter_native_splash:create --path=splashscreen.yaml`
- run the app `flutter run -d chrome`





