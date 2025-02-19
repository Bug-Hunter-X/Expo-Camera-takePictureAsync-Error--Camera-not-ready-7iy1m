# Expo Camera takePictureAsync Error: Camera Not Ready

This repository demonstrates a common error encountered when using the Expo Camera API: calling `takePictureAsync` before the camera has finished initializing.  The example shows how to reproduce the error and provides a solution to prevent it.

## Reproducing the Error

The `bug.js` file contains code that attempts to call `takePictureAsync` too early, resulting in an error.  Run this file to see the error in action. 

## Solution

The `bugSolution.js` file demonstrates a corrected approach, ensuring that `takePictureAsync` is only called after the camera has fully initialized and is ready to capture images.