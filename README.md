# Pastel
Instagram like Gradient background animation

[![CI Status](http://img.shields.io/travis/cruz/Pastel.svg?style=flat)](https://travis-ci.org/cruz/Pastel)
[![Version](https://img.shields.io/cocoapods/v/Pastel.svg?style=flat)](http://cocoapods.org/pods/Pastel)
[![License](https://img.shields.io/cocoapods/l/Pastel.svg?style=flat)](http://cocoapods.org/pods/Pastel)
[![Platform](https://img.shields.io/cocoapods/p/Pastel.svg?style=flat)](http://cocoapods.org/pods/Pastel)

![pastel_01.gif](README/Pastel_01.gif)
![pastel_02.gif](README/Pastel_02.gif)
![pastel_03.gif](README/Pastel_03.gif)

## Example
```swift
override func viewDidLoad() {
    super.viewDidLoad()

    let pastelView = PastelView(frame: view.bounds)
    pastelView.setColors(colors: [.blue, .white, .black]) // set custom colors
    pastelView.addColor(color: .red)
    pastelView.animationDuration = 2.5
    pastelView.startAnimation()
    view.insertSubview(pastelView, at: 0)
}
```

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements
Pastel is written in Swift 3. iOS 8.0+ Required

## Installation

Pastel is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "Pastel"
```

## Author

cruz, cruzdiary@gmail.com

## License

Pastel is available under the MIT license. See the LICENSE file for more info.
