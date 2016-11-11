# TMapSDK
### SK planet TMap SDK cocoa pods

https://developers.skplanetx.com/develop/doc/sdk/tmap-sdk-ios/

- Swift 일경우, Bridging-Header.h 에 아래 내용 추가.
```
#import <TMapSDK/TMapView.h>
```

- Podfile 사용 예
```
source 'https://github.com/CocoaPods/Specs.git'
source 'https://github.com/Posteet/Specs.git'

# Uncomment this line to define a global platform for your project
platform :ios, '8.0'
# Uncomment this line if you're using Swift
use_frameworks!

target 'Sample' do
    pod 'TMapSDK'
end
```
