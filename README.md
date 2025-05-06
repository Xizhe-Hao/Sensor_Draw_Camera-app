# Sensor_Draw_Camera-app
   # Multi-Feature Android Application

## Overview
This Android application demonstrates the implementation of multiple hardware features available on modern Android devices. The app consists of three main tabs: Sensors, Draw, and Camera, each showcasing different device capabilities.

## Features

### Sensors Tab
- Displays real-time data from three device sensors:
  - Accelerometer: Shows X, Y, Z axis movement data
  - Proximity: Detects distance between device and objects
  - Light: Measures ambient light levels
- Gracefully handles missing sensors with user notifications
- Updates sensor readings in real-time

### Draw Tab
- Allows users to select images from their device gallery
- Provides a drawing interface to draw over selected images
- Includes color selection (black and red) for drawing
- Supports saving edited images to the device gallery
- Includes a reset feature to restore the original image

### Camera Tab
- Implements a full camera interface using CameraX library
- Supports both front and rear cameras with easy switching
- Captures photos and displays them in the app
- Saves captured photos to the device gallery
- Handles camera permissions properly

## Technical Implementation
- Built with Kotlin following modern Android development practices
- Uses Navigation Component for tab navigation
- Implements View Binding for safer view access
- Properly handles runtime permissions for camera and storage
- Compatible with different Android versions (API 24+)
- Implements proper lifecycle management for all components

## Setup Instructions

### Prerequisites
- Android Studio Giraffe (2023.3.1) or newer
- Minimum SDK 24 (Android 7.0)
- Target SDK 34 (Android 14)

### Building the Project
1. Clone the repository
2. Open the project in Android Studio
3. Sync Gradle files
4. Build and run on a physical device (emulators may not support all sensors)

## Permissions
This app requires the following permissions:
- Camera access
- Storage read/write access
- Sensor access

These permissions are requested at runtime with proper handling of user responses.  

## Troubleshooting
If you encounter any issues:
1. Make sure all dependencies are properly synced
2. Verify that the necessary permissions are granted in app settings
3. Use a physical device rather than an emulator for full functionality
4. Check that all required resources exist in the project