# Devui

**Devui** is a super lightweight companion app for DEV authors. 

It allows you to quickly see your posts' metadata and statistics.

## How to use it

Create a new API key from your [DEV Dashboard](https://dev.to/settings/account)
and paste it inside Devui to immediately fetch all your published and
unpublished articles.

Your API key is saved on the device's UserDefaults and is only sent when making
requests to the [DEV API](https://docs.dev.to/api/).

## Tech stack

This app was created using SwiftUI and Combine, two of Apple's most exciting new
tools introduced with iOS 13.0.

All network requests are handled through Combine publishers.

The various components are connected following the MVVM pattern.

This app is fully localizable, accessibility-friendly, supports dark mode and
uses iOS 13's semantic colors.

### Dependencies

This app's only dependency is installed through Swift Package Manager and
provides a lightweight dependency injection framework.

* [hmlongco/Resolver](https://github.com/hmlongco/Resolver)
