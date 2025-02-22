Horizon SDK for iOS
=======================

<img src="https://horizon.camera/static/sdk/docs/docs/documentation-static/images/horizonsdk-logo.png" alt="Horizon SDK logo" style="width:112px;height:112px;">

Horizon SDK is a state of the art real-time video recording / photo shooting iOS library.

Some of the features of Horizon SDK include:

* Horizon real-time leveling algorithm (you can find more at [https://horizon.camera](https://horizon.camera))
* Support for multiple resolutions (up to 2K recording) and frame rates.
* Custom filter support using the Core Image framework.
* Multiple previews.
* A simple view controller that makes integrating the SDK to your app really easy.
* Access to the video buffer so that it can be further processed or live streamed using other libraries.

In order to use Horizon SDK on your app, you have to register for an account at [https://horizon.camera/sdk](https://horizon.camera/sdk), create an app and receive your API key. The provided sample apps contain their own API keys.

The library can be used on devices running iOS version 7.1 or higher.  You can build your application using Xcode 6 or higher.

For more information take a look at the [Installation](https://horizon.camera/static/sdk/docs/docs/documentation-static/Installation%20Guide.html) and [Quick Start](https://horizon.camera/static/sdk/docs/docs/documentation-static/Quick%20Start.html) guides of the [documentation](https://horizon.camera/sdk/docs/).

Examples
--------

There are three Xcode projects in the Examples directory with examples of how to create a simple video recording application, a more advanced use of the library and a Swift project. 

* The **HorizonSDKDemo** example app demonstrates the same basic functionality of the HorizonSDK: Creating a preview, instanciating the camera and having a record button. HorizonSDKDemo requires iOS 7.1 or later.

* The **AdvancedHorizonSDKDemo** example app demonstrates a more advanced functionality of the HorizonSDK: There are two previews, a simple and a leveled one. The app responds to device orientation events and demonstrates some of the features available on HorizonSDK. AdvancedHorizonSDKDemo requires iOS 7.1 or later.

* The **SwiftHorizonSDKDemo** example app provides a simple app written in Swift that shows how to integrate HorizonSDK library with a Swift project. SwiftHorizonSDKDemo requires iOS 8.4 or later.
