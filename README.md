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
  implementation 'com.cascade:pci-sdk:1.0.4'
  ...
}
```

# Releases

## 1.0.4
  * Provided ability to copy card data from virtual cards
  * Optimized code entry field

## 1.0.3
  * Bugfix for initialization of SDK
  * Allow user to pass in wearable card and name and show new wearable screen when card is a wearable

## 1.0.2
  * Allow wearable cards to be displayed in the same way virtual cards are displayed.
