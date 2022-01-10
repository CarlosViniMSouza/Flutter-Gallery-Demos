# flutter_gallery

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Running Flutter Gallery on Flutter's master channel

The Flutter Gallery targets Flutter's master channel. As such, it can take advantage
of new SDK features that haven't landed in the stable channel.

If you'd like to run the Flutter Gallery, make sure to switch to the master channel
first:

```bash
flutter channel master
flutter upgrade
```

When you're done, use this command to return to the safety of the stable
channel:

```bash
flutter channel stable
flutter upgrade
```

## Supported Platforms

Flutter Gallery has been built to support multiple platforms.
This includes:

- Android
- iOS
- web
- macOS
- Linux
- Windows

An APK, macOS, Linux, and Windows builds are available for [download](https://github.com/flutter/gallery/releases). You can find it on the web at [gallery.flutter.dev](https://gallery.flutter.dev/) and on the [Google Play Store](https://play.google.com/store/apps/details?id=io.flutter.demo.gallery).

You can build from source yourself for any of these platforms, though, please note desktop support must [be enabled](https://github.com/flutter/flutter/wiki/Desktop-shells#tooling). For
example, to run the app on Windows:

```bash
cd gallery/
flutter config --enable-windows-desktop
flutter pub get
flutter run -d windows
```

Additionally, the UI adapts between mobile and desktop layouts regardless of the
platform it runs on. This is determined based on window size as outlined in
[adaptive.dart](lib/layout/adaptive.dart).