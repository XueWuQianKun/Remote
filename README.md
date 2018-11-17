# LYTestGitRemote

[![CI Status](https://img.shields.io/travis/XueWuQianKun/LYTestGitRemote.svg?style=flat)](https://travis-ci.org/XueWuQianKun/LYTestGitRemote)
[![Version](https://img.shields.io/cocoapods/v/LYTestGitRemote.svg?style=flat)](https://cocoapods.org/pods/LYTestGitRemote)
[![License](https://img.shields.io/cocoapods/l/LYTestGitRemote.svg?style=flat)](https://cocoapods.org/pods/LYTestGitRemote)
[![Platform](https://img.shields.io/cocoapods/p/LYTestGitRemote.svg?style=flat)](https://cocoapods.org/pods/LYTestGitRemote)

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

## Installation

LYTestGitRemote is available through [CocoaPods](https://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
 pod 'LYTestGitRemote', '~> 0.3.0'
```

## 用法
```ruby
@implementation CDPButton{
CGRect _imageRect;
CGRect _titleRect;
}
-(instancetype)initWithFrame:(CGRect)frame imageRect:(CGRect)imageRect titleRect:(CGRect)titleRect{
if (self=[super initWithFrame:frame]) {
_imageRect=imageRect;
_titleRect=titleRect;
}
    return self;
}
//设置image的范围
- (CGRect)imageRectForContentRect:(CGRect)contentRect{
    return _imageRect;
}
//设置title的范围
- (CGRect)titleRectForContentRect:(CGRect)contentRect{
    return _titleRect;
}
```
## Author

雪飘, iOSDev

## License

LYTestGitRemote is available under the MIT license. See the LICENSE file for more info.
