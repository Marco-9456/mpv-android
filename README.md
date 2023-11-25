<img width="" src="fastlane/metadata/android/en-US/images/icon.png"  width=160 height=160>

# mpv for Android

mpv-android is a versatile video player for Android, leveraging the power of [libmpv](https://github.com/mpv-player/mpv). With advanced playback features and customization options, it provides an unparalleled viewing experience on Android devices.

[![Build Status](https://github.com/mpv-android/mpv-android/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/mpv-android/mpv-android/actions/workflows/build.yml)

## Features

* **Hardware and Software Video Decoding**: Optimal playback performance with both hardware and software decoding.
* **Advanced Video Settings**: Customize interpolation, debanding, scalers, and more for a tailored viewing experience.
* **Gesture-Based Controls**: Intuitive seeking, volume, and brightness controls through simple gestures.
* **Subtitles and More**: Enjoy styled subtitles with libass support and secondary subtitle options for dual viewing.
* **Network Stream Playback**: Easily play network streams with the "Open URL" function.
* **Background Modes**: Supports background playback and Picture-in-Picture for multitasking.

>[!Note]
mpv-android is a standalone app and not a library for embedding. For developers, key components like [`MPVLib`](app/src/main/java/is/xyz/mpv/MPVLib.java), [`MPVView`](app/src/main/java/is/xyz/mpv/MPVView.kt), and the [native code](app/src/main/jni/) can offer valuable insights.

## Downloads

Get the latest version of mpv-android from the [Releases section](https://github.com/mpv-android/mpv-android/releases), Google Play, or F-Droid:

<a href="https://play.google.com/store/apps/details?id=is.xyz.mpv"><img src="https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png" alt="Download from Google Play" height="80"></a>
<a href="https://f-droid.org/packages/is.xyz.mpv"><img src="https://f-droid.org/badge/get-it-on.png" alt="Get it on F-Droid" height="80"></a>
<a href="https://github.com/mpv-android/mpv-android/releases"><img src="https://raw.githubusercontent.com/vadret/android/master/assets/get-github.png" alt="Get it on Github" height="80"></a>

## Building from Source

For those interested in building mpv-android from source, start by reviewing the [README.md](buildscripts/README.md) in the `buildscripts` directory. It provides a comprehensive guide, including prerequisites and step-by-step instructions.

## Contributing

We welcome contributions to mpv-android! If you're interested in contributing, please review our contribution guidelines, which include information on coding standards and how to submit pull requests.

## Support

Experiencing issues or have questions? Feel free to reach out or report bugs through our [Issues page](https://github.com/mpv-android/mpv-android/issues).
