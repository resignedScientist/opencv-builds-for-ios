# opencv-builds-for-ios

Pre-Build OpenCV Versions for iOS.

They are all built for:
- iOS Devices
- iOS Simulator (Intel + Apple Silicon)

This is the build command:

```
python3 platforms/apple/build_xcframework.py --out build --iphoneos_archs arm64 --iphonesimulator_archs arm64,x86_64 --build_only_specified_archs
```

