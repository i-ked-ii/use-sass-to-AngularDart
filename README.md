# วิธีการใช้ sass ใน Dart Angular อย่างง่าย
How to Use SASS with Dart Angular

## install sassc
[brew install sassc](https://github.com/dart-league/dart-sass)

## How to use
1. Depend on it
Add this to your package's `pubspec.yaml` file
```
dependencies:
   dart_sass_transformer: any
transformers:
  - dart_sass_transformer:
     executable: sassc
```
2. Install it
You can install packages from the command line
```
pub get
```
