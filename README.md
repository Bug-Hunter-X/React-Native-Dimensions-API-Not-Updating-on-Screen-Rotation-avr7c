# React Native Dimensions API Not Updating on Screen Rotation

This repository demonstrates a common issue in React Native applications where the `Dimensions` API fails to update the screen dimensions when the device's orientation changes.  The provided code showcases the problem and offers a solution using the `Dimensions` API's `addEventListener` method.

## Problem
The `Dimensions` API in React Native provides the screen dimensions, but it only provides the initial dimensions at component mount.  When the screen rotates, the dimensions remain unchanged unless the component is remounted or an event listener is added.

## Solution
Using the `addEventListener` method of `Dimensions` allows listening for orientation changes and updating the dimensions accordingly. This ensures the application correctly responds to dynamic screen changes.

## How to Run
1. Clone this repository.
2. Run `npm install` or `yarn install`.
3. Run the app using `react-native run-android` or `react-native run-ios`.