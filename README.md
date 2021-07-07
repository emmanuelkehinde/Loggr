# Loggr

A simple logging solution for your iOS projects.

<img src=https://github.com/emmanuelkehinde/Loggr/raw/master/loggr.gif alt="Loggr" height=400/>

### Installation

Here is how to integrate the library in your iOS project.

#### Swift Package Manager

- File > Swift Packages > Add Package Dependency
- Add `https://github.com/emmanuelkehinde/Loggr.git`
- Select "Up to Next Major" with "1.0.0"

### Usage

```swift
import Loggr

// Debug
Loggr.logDebug("Debug Message")

// Info
Loggr.logInfo("Info Message")

// Error
Loggr.logError("Error Message")

// Warning
Loggr.logWarning("Warning Message")
```
