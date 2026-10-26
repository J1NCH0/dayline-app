# dayline-app

SwiftUI app for [Dayline](../README.md). One codebase for **iPhone (iOS 17+)** and **Mac (macOS 14+)**.

> Early development. This is currently the default SwiftUI template.

## Requirements

- Xcode 16+
- [XcodeGen](https://github.com/yonaskolb/XcodeGen): `brew install xcodegen`

## Getting started

The Xcode project is generated from [`project.yml`](project.yml). Edit that file (not the `.xcodeproj`) to change targets, settings or files, then regenerate:

```sh
xcodegen generate
open Dayline.xcodeproj
```

In Xcode, pick your team under **Signing & Capabilities** and run the **Dayline** scheme on an iPhone simulator or *My Mac*.

## Structure

```
Dayline/
├── DaylineApp.swift      # app entry point
├── ContentView.swift
└── Assets.xcassets       # app icon, accent color
project.yml               # XcodeGen spec
```
