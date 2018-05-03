# use-sass-to-AngularDart
How to Use SASS with Dart Angular
# install
  brew install sassc
https://github.com/dart-league/dart-sass

# How to use
1. Add it to pubspec.yaml

dependencies:
   dart_sass_transformer: any
transformers:
   dart_sass_transformer:
     executable: sassc
  
2. And do pub get
