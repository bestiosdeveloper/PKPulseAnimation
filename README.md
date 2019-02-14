# PKPulseAnimation

A Swift based helper class that will provide the pulse animation.


## Requirements

- iOS 10.0+
- Xcode 9.4

## Installation

Just download the file and place in your Xcode project.

## Usage

Example:

```swift

//create a object for PKPulseAnimation.
private var pulsAnimation = PKPulseAnimation()

//configure the PKPulseAnimation object
//`containerView` is the UIView that contains `button` as UIButton inside it.
self.pulsAnimation.numPulse = 6
self.pulsAnimation.radius = 100.0
self.pulsAnimation.currentAnimation = .line
self.pulsAnimation.lineWidth = 2.0
self.pulsAnimation.lineColor = UIColor.red
self.pulsAnimation.backgroundColor = UIColor.clear
self.containerView.layer.insertSublayer(self.pulsAnimation, below: self.button.layer)
```

## Licence

PKLoader is released under the MIT license.











