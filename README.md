# Flutter QRCode Scanner APP

Olá, pessoal

![Image](fa.png)

## Getting Started

### Flutter Project

* Add this to your package's pubspec.yaml file:

  `dependencies: barcode_scan: "^1.0.0"`

### Android

For Android, you must do the following before you can use the plugin:

* Add the camera permission to your AndroidManifest.xml

  `<uses-permission android:name="android.permission.CAMERA" />`

* Add the Barcode activity to your AndroidManifest.xml
  `<activity android:name="com.apptreesoftware.barcodescan.BarcodeScannerActivity"/>`

### iOS

To use on iOS, you must add the the camera usage description to your Info.plist

    <key>NSCameraUsageDescription</key>
    <string>Camera permission is required for barcode scanning.</string>

