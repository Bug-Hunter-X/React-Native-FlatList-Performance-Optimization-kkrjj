# React Native FlatList Performance Optimization

This repository demonstrates a common performance issue in React Native's FlatList component when dealing with large datasets and provides a solution for optimization.

## Bug
The initial implementation of FlatList suffers from slow scrolling and potential crashes due to inefficient rendering and key management. The `renderItem` function might also be doing too much work.

## Solution
The solution focuses on improving key generation using the `keyExtractor` prop and optimizing the data structure for faster rendering.  Unnecessary operations are removed from `renderItem` function.   Improvements in data handling and rendering significantly enhance performance.

## Usage
Clone the repository and run `npx react-native run-android` or `npx react-native run-ios`.