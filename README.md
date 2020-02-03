# Amahi iOS App
Amahi iOS App, new from scratch, in Swift.

[![Build Status](https://travis-ci.org/amahi/ios.svg?branch=master)](https://travis-ci.org/amahi/ios) `master`

[![Build Status](https://travis-ci.org/amahi/ios.svg?branch=beta)](https://travis-ci.org/amahi/ios) `beta`

## Requirements

- iOS 9.0+
- Xcode 9.0+

## Setup
- Close Xcode
- Open a terminal window, and `$ cd` into your project directory.
- Run `$ pod install`
- You may require to run `$ pod update`
- `$ open AmahiAnywhere.xcworkspace` and build.
- The build may fail with a missing ApiConfig.swift file
- This file has developer/production credentials/endpoints and should not be shared. Email support at amahi dot org a copy of this file. 

### Code Practices
Please help us follow the best practice to make it easy for the reviewer as well as the contributor.
* Please follow the guides and code standards: [Swift Style Guide](https://github.com/linkedin/swift-style-guide)
* Please follow the good iOS development practices: [iOS Good Practices](https://github.com/futurice/ios-good-practices)
* If the PR is related to any front end change, please attach relevant screenshots in the pull request description.

### Pods
- [Alamofire](https://github.com/Alamofire/Alamofire): Elegant HTTP Networking in Swift

- [EVReflection](https://github.com/evermeer/EVReflection): Reflection based (Dictionary, CKRecord, NSManagedObject, Realm, JSON and XML) object mapping with extensions for Alamofire

- [IQKeyboardManagerSwift](https://github.com/hackiftekhar/IQKeyboardManager): Codeless drop-in universal library allows to prevent issues of keyboard sliding up and cover UITextField/UITextView with one line of code

- [MBProgressHUD](https://github.com/jdg/MBProgressHUD): It is an iOS drop-in class that displays a translucent HUD with an indicator and/or labels while work is being done in a background thread.

- [MobileVLCKit](https://code.videolan.org/videolan/VLCKit.git): It is an Objective-C wrapper for libvlc's external interface on iOS.

- [SkyFloatingLabelTextField](https://github.com/Skyscanner/SkyFloatingLabelTextField): A beautiful and flexible text field control implementation of "Float Label Pattern". Written in Swift.

- [LightBox](https://github.com/hyperoslo/Lightbox): Provides a convenient and easy to use image viewer for iOS app, packed with with features like swipe left/right to change, double tap to zoom, pinch to zoom, caching etc.
- [Cache](https://github.com/hyperoslo/Cache): Cache doesn't claim to be unique in this area, but it's not another monster library that gives you a god's power. It does nothing but caching, but it does it well. It offers a good public API with out-of-box implementations and great customization possibilities. 

- [Floaty](https://github.com/kciter/Floaty): Floaty is simple floating action button for iOS. (formerly KCFloatingActionButton)

- [google-cast-sdk](https://cocoapods.org/pods/google-cast-sdk): Google Cast is a screen-sharing technology that lets a user send and
control content like video from a small computing device like a phone, tablet, or laptop to a large display device like a television.

- [Imaginary](https://github.com/hyperoslo/Imaginary): Using remote images in an application is more or less a requirement these days. This process should be easy, straight-forward and hassle free, and with Imaginary, it is. The library comes with a narrow yet flexible public API and a bunch of built-in unicorny features

- [Protobuf](https://github.com/protocolbuffers/protobuf): Protocol Buffers (a.k.a., protobuf) are Google's language-neutral, platform-neutral, extensible mechanism for serializing structured data.

- [ReachabilitySwift](https://github.com/ashleymills/Reachability.swift): Reachability.swift is a replacement for Apple's Reachability sample, re-written in Swift with closures.

- [SDWebImage](https://github.com/SDWebImage/SDWebImage): This library provides an async image downloader with cache support. For convenience, we added categories for UI elements like UIImageView, UIButton, MKAnnotationView.

- [SwipeCellKit](https://github.com/SwipeCellKit/SwipeCellKit): A swipeable UITableViewCell or UICollectionViewCell
## Support

If you have questions about Amahi or just want to interact, you can contact us via [IRC channel](http://talk.amahi.org). Don't forget that we are open to suggestions, extensions or adaptations. Feel free to discuss or propose new ideas for projects!


This app will go into the [iOS app store](https://itunes.apple.com/us/app/amahi/id761559919) and replace the current version there written in Objective C.
