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


A widget to toggle between a light or dark ThemeMode 






## Features
Configurable colors for background and foreground colors for both light and dark modes
API similar to standard Material Slider widget



TODO: List what your package can do. Maybe include images, gifs, or videos.

## Getting started
Flutter Android
Flutter iOS
Flutter Web
Flutter Desktop


TODO: List prerequisites and provide or point to information on how to
start using the package.

## Usage

TODO: Include short and useful examples for package users. Add longer examples
to `/example` folder. 

```dart
Widget build(BuildContext context) {
  return Scaffold(
    appBar: AppBar(
      title: Text(title),
    ),
    body: Center(
      child: ThemeModeSelector(
        height: 39,
        onChanged: (mode) {
          print('ThemeMode changed to $mode');
          ThemeModeManager.of(context).themeMode = mode;
        },
      ),
    ),
  );
}
```

## Additional information



TODO: Tell users more about the package: where to find more information, how to 
contribute to the package, how to file issues, what response they can expect 
from the package authors, and more.
#   d a y _ n i g h t _ s w i t c h  
 #   d a y _ n i g h t _ s w i t c h  
 