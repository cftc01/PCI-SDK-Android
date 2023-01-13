# Android PCI SDK

To use this package include the following in your project's `settings.gradle` file

```
dependencyResolutionManagement {
  ...
  repositories {
    ...
    maven { url 'https://raw.githubusercontent.com/cftc01/PCI-SDK-Android/main/maven' }
  }
}
```

You can then include it in your app's `build.gradle` file

```
dependencies {
  ...
  implementation 'com.cascade:pci-sdk:1.0.0'
  ...
}
```
