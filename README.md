# React Native FlatList Separator Bug

This repository demonstrates a common bug encountered when using FlatList in React Native with large datasets and custom item separators. The bug manifests as misaligned or missing separators, creating visual inconsistencies.

## Bug Description

The issue occurs because of incorrect handling or measurement calculations within the custom separator component. This often leads to visual errors and incorrect layout behavior. 

## Solution

The solution involves careful handling of the separator's dimensions and accurate measurements to ensure proper alignment.  The `FixedFlatList.js` file provides a corrected implementation.

## Setup

1. Clone the repository.
2. Navigate to the project directory.
3. Run `npm install` to install dependencies.
4. Run `npx react-native run-android` or `npx react-native run-ios` to run the app.