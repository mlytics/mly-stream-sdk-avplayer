# 指定工作空间
workspace 'mly-stream-sdk.xcworkspace'


project 'swift-demo'


target 'swift-demo' do 
use_frameworks!
platform :ios, '14.0'
project 'examples/swift-demo/swift-demo.xcodeproj'

pod 'MLYSDK',:git => 'https://github.com/mlytics/mly-stream-sdk-avplayer.git'
pod 'SnapKit', '~> 5.6.0'
end



target 'objective-c-demo' do 
use_frameworks!
platform :ios, '14.0'
project 'examples/objective-c-demo/objective-c-demo.xcodeproj'

pod 'MLYSDK',:git => 'https://github.com/mlytics/mly-stream-sdk-avplayer.git'
end
