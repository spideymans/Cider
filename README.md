# Cider
The Missing Apple Music SDK

[![Build Status](https://travis-ci.org/scottrhoyt/Cider.svg?branch=master)](https://travis-ci.org/scottrhoyt/Cider)
[![codecov.io](https://codecov.io/github/scottrhoyt/Cider/coverage.svg?branch=master)](https://codecov.io/github/scottrhoyt/Cider?branch=master)
[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)
[![CocoaPods](https://img.shields.io/cocoapods/v/Cider.svg)](https://cocoapods.org/pods/Cider)
[![SPM compatible](https://img.shields.io/badge/SPM-compatible-brightgreen.svg)](https://github.com/apple/swift-package-manager)
![Platform iOS](https://img.shields.io/badge/Platform-iOS-blue.svg)
[![Language Swift 4.0](https://img.shields.io/badge/Language-Swift%204.0-orange.svg)](https://swift.org)

### Installation

#### Carthage

Add the following to your Cartfile:

```sh
github "scottrhoyt/Cider" ~> 0.3
```

#### CocoaPods

Add the following to your Podfile:

```sh
pod 'Cider', '~> 0.3'
```

#### SPM

Add to your `Package.swift` file like so:

```swift
import PackageDescription

let package = Package(
    name: "<YOUR_PROJECT_NAME>",
    dependencies: [
        .package(url: "https://github.com/scottrhoyt/Cider.git", from: "0.6.0")
    ]
)
```

### API Reference

The full API reference can be found [here](https://scottrhoyt.github.io/Cider).

### License

MIT
