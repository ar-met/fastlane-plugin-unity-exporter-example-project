# fastlane-plugin-unity-exporter-example-project

This repository contains a new _Unity3d_ project, where _fastlane_ was setup for _Android_ and _iOS_ by following the steps described in [this readme](https://github.com/ar-met/fastlane-plugin-unity-exporter#getting-started-with-a-blank-unity3d-project).

There now exists a [_Fastfile for Android_](fastlane-build-exporter/Android/fastlane/Fastfile) and a [_Fastfile for iOS_](fastlane-build-exporter/iOS/fastlane/Fastfile). Note that these _Fastfiles_ contain the lane *custom_lane*, which shows an example usage of the _fastlane plugin_ [*unity_exporter*](https://github.com/ar-met/fastlane-plugin-unity-exporter).

To execute Android's *custom_lane* navigate to `fastlane-build-exporter/Android` in your terminal and execute `fastlane custom_lane`. 

To execute iOS' *custom_lane* navigate to `fastlane-build-exporter/iOS` in your terminal and execute `fastlane custom_lane`. 
