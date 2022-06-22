<!-- 
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/guides/libraries/writing-package-pages). 

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-library-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/developing-packages). 
-->

A fork of Bear-Dictionary's fork of Flutter Gradients. The null-safe changes he added are merged into the main branch and files are moved around to allow this repository to be used as a flutter dependancy. Even after merging in the null-safe changes, Flutter was still seeing it as a legacy package so I redid the pubspec.yaml file to the current template as well as all other non-library files.

Hopefully Jonathan Monga will get the original up to null saftey and this fork will no longer be necessary.

Original repository: https://github.com/JonathanMonga/flutter_gradients

null-safe changes by Bear-Dictionary: https://github.com/Bear-Dictionary/flutter_gradients

To use in your flutter project add following to pubspec.yaml:

dependencies:
  flutter_gradients:
    git:
      url: https://github.com/ShadowOfThePenguin/flutter_gradients.git
