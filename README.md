# Android PCI SDK

To use this package include the following in your project's `settings.gradle` file

```
dependencyResolutionManagement {
  ...
  repositories {
    ...
    maven { url 'https://raw.githubusercontent.com/cftc01/PCI-SDK-Android/master/maven' }
  }
}
```

You can then include it in your app's `build.gradle` file

```
dependencies {
  ...
  implementation 'com.cascade:pci-sdk:1.0.2'
  ...
}
```

# Releases

## 1.0.2
  * Allow wearable cards to be displayed in the same way virtual cards are displayed.
