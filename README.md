# Tuya Smart Home iOS SDK - Specs (arm64 Simulator Support)

This repository contains CocoaPods specifications for Tuya Smart Home iOS SDK with arm64 simulator support.

## What's Different?

- ✅ **arm64 simulator support** (Apple Silicon Macs)
- ✅ All original functionality preserved
- ✅ Same API as official SDK
- ✅ Updated for iOS 11.0+

## Installation

Add this to your `Podfile`:

```ruby
source 'https://github.com/programming086/TuyaSimulatorFixed-Specs.git'
source 'https://github.com/CocoaPods/Specs.git'

platform :ios, '11.0'

target 'YourApp' do
  use_frameworks!
  
  # Main activation kit (includes device pairing, network config, etc)
  pod 'TuyaSmartActivatorKit'
  
  # Or use specific modules
  # pod 'TuyaSmartDeviceKit'
  # pod 'TuyaSmartBaseKit'
end
```

Then run:

```bash
pod install
```

## Repository Structure

Specs/
├── TuyaSmartActivatorKit/
│   └── 4.0.0/
│       └── TuyaSmartActivatorKit.podspec.json
├── TuyaSmartBaseKit/
│   └── 4.0.0/
│       └── TuyaSmartBaseKit.podspec.json
└── ...

## Binaries Repository

The actual XCFramework binaries are stored in a separate repository:
https://github.com/programming086/TuyaSimulatorFixed-Binaries

This separation keeps the specs repo lightweight for faster `pod install`.

## Available Frameworks

Check the `Specs/` directory for all available frameworks and their versions.

## Updates

To update to a new version of the official SDK:
1. Run the patching scripts on the new version
2. Update this specs repository
3. Tag new versions in the binaries repository

## Support

For issues related to:
- **arm64 simulator support**: Open an issue in this repository
- **Tuya SDK functionality**: Check [official Tuya documentation](https://developer.tuya.com/en/docs/iot)

## License

The frameworks themselves are licensed by Tuya Inc.
This repository only provides arm64 simulator patches.
