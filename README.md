# Tuya Smart Home iOS SDK - CocoaPods Specs (arm64 Simulator Support)

This repository contains CocoaPods specifications for Tuya Smart Home iOS SDK with arm64 simulator support.

## ✨ What's Different?

- ✅ **arm64 simulator support** (Apple Silicon Macs)
- ✅ All original functionality preserved
- ✅ Same API as official SDK
- ✅ Fast installation via direct HTTP downloads

## 🚀 Installation

Add this to your `Podfile`:

```ruby
source 'https://github.com/programming086/TuyaSimulatorFixed-Specs.git'
source 'https://github.com/CocoaPods/Specs.git'

platform :ios, '11.0'

target 'YourApp' do
  use_frameworks!
  pod 'TuyaSmartActivatorKit'
end
```

Then run:

```bash
pod install
```

## ⚡ Why is it Fast?

Unlike the original Tuya specs that clone entire git repositories, our specs use **direct HTTP downloads** from GitHub Releases. This makes installation much faster!

## 📦 Swift Package Manager

Prefer SPM? Check out: https://github.com/programming086/TuyaSimulatorFixed-SPM

## 📚 Available Frameworks

Check the `Specs/` directory for all available frameworks and their versions.

## 🔗 Related Repositories

- **Binaries**: https://github.com/programming086/TuyaSimulatorFixed-Binaries (GitHub Releases with ZIPs)
- **SPM**: https://github.com/programming086/TuyaSimulatorFixed-SPM (Swift Package Manager)
