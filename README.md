# Library Calculator

A SwiftUI iOS project by Logan Voss.

## Current state

The checked-in app is a starter scaffold displaying a globe symbol and “Hello, world!”. Library or calculator functionality is not implemented in this snapshot.

## Open and run

Use a Mac with Xcode and an iOS Simulator runtime compatible with the project's iOS 18.4 deployment target. The project was created with Xcode 16.3.

```bash
git clone https://github.com/LoganVoss/Library-Calculator.git
cd Library-Calculator
open LibraryCalculator.xcodeproj
```

1. Select the `LibraryCalculator` scheme in Xcode.
2. Choose an iPhone or iPad simulator running iOS 18.4 or later.
3. Choose **Product → Run** (⌘R).

For a physical device, select your own development team under **Signing & Capabilities** and use a unique bundle identifier if required. No third-party Swift package dependencies are declared in the project.

## Project guide

- [LibraryCalculator/ContentView.swift](LibraryCalculator/ContentView.swift): starter screen and SwiftUI preview.
- [LibraryCalculator/LibraryCalculatorApp.swift](LibraryCalculator/LibraryCalculatorApp.swift): application entry point.
- [LibraryCalculator/Assets.xcassets](LibraryCalculator/Assets.xcassets): asset catalog.
- [LibraryCalculator.xcodeproj](LibraryCalculator.xcodeproj): Xcode project and build settings.
- [LibraryCalculatorTests](LibraryCalculatorTests): Swift Testing target with an empty example test.
- [LibraryCalculatorUITests](LibraryCalculatorUITests): XCTest launch, launch-performance, and screenshot tests.

## Build and test

In Xcode, use **Product → Build** (⌘B) or **Product → Test** (⌘U) with a compatible simulator selected.

The included tests are starter tests, not coverage of calculator behavior. No CI workflow is currently included. These instructions are based on the checked-in source and project settings; no successful build or test run is asserted here.
