# Sample Application for IBM Navigator Mobile SDK for iOS

Sample Application to demonstrate the features of IBM Navigator Mobile SDK for iOS

** This Sample app will not compile without the IBM Navigator SDK binary framework. IBM Navigator Mobile 3.3.0 SDK is required. Please refer to the README pdf for detailed instructions on how to obtain it. It only compiles against Swift 3.1 and Xcode 8.3.* currently. ** 

## Usage

Simply place IBMECMCore.framework in the same folder as the workspace file (not the project file,) build and run on simulator. You can connect only to IBM Content Navigator 2.0.3 fixpack 5 backend environments (more information [here](http://www-03.ibm.com/software/products/en/content-navigator))

## Documention
The latest SDK Documentation can be found here: http://ibm-ecm.github.io/ibm-navigator-mobilesdk-sample/ 

## Screenshots

### Login
![](https://raw.githubusercontent.com/kosta-tachtevrenidis/ibm-navigator-mobilesdk-sample/master/screenshots/login.png)

### Browse
![](https://raw.githubusercontent.com/kosta-tachtevrenidis/ibm-navigator-mobilesdk-sample/master/screenshots/browse.png)

### Search
![](https://raw.githubusercontent.com/kosta-tachtevrenidis/ibm-navigator-mobilesdk-sample/master/screenshots/search.png)

## Misc

The Xcode project is meant to be used with Cocoapods. For simplicity, we have included the 'Pods' generated project. You can generate your own by executing 'pod install' inside the folder with the workspace file. See documentation on how to install cocoapods on your development workstation.
