UIImageView+Extension ![Supported Platforms](https://img.shields.io/cocoapods/p/UIImageView+Extension.svg) [![Latest pod release](https://img.shields.io/cocoapods/v/UIImageView+Extension.svg)](https://cocoapods.org/pods/UIImageView+Extension) [![Build Status](https://travis-ci.org/alexandreos/UILabel-Copyable.svg?branch=master)]() [![License](https://img.shields.io/cocoapods/l/UIImageView+Extension.svg)](https://github.com/lm2343635/UIImageView-Extension/LICENSE)
===
A simple UIImageView category with some extension functions.

# Features
- Supports Interface Builder.
- Set border radius for image view.
- Set shadow for image view.

# Installation

### CocoaPods
Installing UIImageView+Extension by [CocoaPods](http://cocoapods.org/). 

```ruby
pod 'UILabel+Copyable', '~> 1.0.0'
```
### Old-fashioned way

- Add `UIImageView+Extension.h` and `UIImageView+Extension.m` to your project.
- `#import "UIImageView+Extension.h"` where you want to use the control.
- These files require **ARC**.

# Usage

If you just want to set features in Interface Builder, just do it in Interface Builder, you need not to do anything.
![Interface Builder Guide](https://raw.githubusercontent.com/lm2343635/UIImageView-Extension/master/Screenshoots/InterfaceBuilderGuide.png)
If you want to control your image view in your program, you should import the category header: `#import "UIImageView+Extension.h"` to your `.h` or `.m` file.
