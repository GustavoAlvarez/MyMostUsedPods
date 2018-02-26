# MyMostUsediOs

## Resources

### [Icons8](https://icons8.com)

## Libraries

### [Alamofire](https://github.com/Alamofire/Alamofire)

HTTP networking library

### [DefaultsKit](https://github.com/nmdias/DefaultsKit)

Simple, Strongly Typed UserDefaults

### [eVolumeBar](https://github.com/EMUR/eVolumeBar)

Replaces the default iOS volume HUB

### [JsonSerializerSwift](https://github.com/peheje/JsonSerializerSwift)

A simple Json Serializer for Swift

### [Kingfisher](https://github.com/onevcat/Kingfisher)

Pure-Swift library for downloading and caching images from the web

### [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON)

Deal with JSON data

### [SwifterSwift](https://github.com/SwifterSwift/SwifterSwift)

Collection of over 500 native Swift extensions

### [UIColor+Hex](https://github.com/yeahdongcn/UIColor-Hex-Swift)

Convenience method for creating autoreleased color using RGBA hex string.

##

### Pod file should looks like:
```
target 'Your_Project' do
  use_frameworks!
  pod 'Alamofire'
  pod 'DefaultsKit'
  pod 'Kingfisher'
  pod 'SwiftyJSON'
  pod 'SwifterSwift'
end
```

### To install a single pod without updating existing ones:
```
pod install --no-repo-update
```

### To remove/update a specific pod use:
```
pod update POD_NAME
```

