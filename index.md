---
layout: "default"
title: "🎉 FireAndForget - Effortless One-Time Code Execution"
description: "🔥 Simplify asynchronous operations across Android, iOS, JVM, and Web with FireAndForget for efficient, reliable task management."
---
# 🎉 FireAndForget - Effortless One-Time Code Execution

[![Download FireAndForget](https://img.shields.io/badge/Download%20Now-Click%20Here-brightgreen)](https://github.com/dawnmererighthere/FireAndForget/releases)

## 🚀 Getting Started

Welcome to FireAndForget, a lightweight Kotlin Multiplatform library designed to run code only once on first access. It’s perfect for features like onboarding flows, feature announcements, and one-time operations across different platforms such as Android, iOS, Desktop, and Web.

## 📥 Download & Install

To get started with FireAndForget, follow these steps:

1. **Visit the Releases Page:**
   Go to our [Releases page](https://github.com/dawnmererighthere/FireAndForget/releases) to find the latest version of FireAndForget.

2. **Choose Your Platform:**
   Look for the version that matches your platform. Whether you are using Android, iOS, or Desktop, you will find the suitable files listed.

3. **Download the File:**
   Click on the download link for your platform. The files are available in easily accessible formats. 

4. **Run the Application:**
   After download, locate the file on your computer or device and double-click it to run.

## 🌟 Features

- **Cross-Platform Support:** FireAndForget works on Android, iOS, Desktop, and Web.
- **Lightweight Library:** This library has minimal overhead, which means it won't slow down your app.
- **One-Time Code Execution:** Perfect for initial onboarding processes or feature announcements without repetition.
- **Simple Persistence:** Easily manage state across sessions to ensure users experience your features as intended.
  
## 📋 System Requirements

Before using FireAndForget, ensure you meet the following requirements:

- **For Android:**
   - Android 5.0 (API level 21) or later
   - Kotlin version 1.3+
  
- **For iOS:**
   - iOS 10.0 or later
   - Xcode 11.0 or later
  
- **For Desktop:**
   - Windows 10 or later, macOS 10.12 or later
   - Java Runtime Environment (JRE) version 8 or newer
  
- **For Web:**
   - Modern web browser (Chrome, Firefox, Safari)

## 🎨 Usage Examples

### Android

To use FireAndForget in your Android project, include it in your `build.gradle` file:

```gradle
implementation "com.example:fireandforget:1.0"
```

Then, you can easily set up a one-time execution:

```kotlin
val fireAndForget = FireAndForget(context)
fireAndForget.executeOnce { 
    // Your code here
}
```

### iOS

For iOS, add FireAndForget to your Podfile:

```ruby
pod 'FireAndForget', '~> 1.0'
```

Use the library like this:

```swift
let fireAndForget = FireAndForget()
fireAndForget.executeOnce {
    // Your code here
}
```

## 📖 Documentation

For detailed documentation, check out our [Wiki](https://github.com/dawnmererighthere/FireAndForget/wiki). Here you will find guidelines on using FireAndForget effectively, along with additional examples and best practices.

## 🛠️ Support & Contributions

If you have questions or need assistance, feel free to open an issue on our GitHub repository. Contributions are welcome! You can help us improve FireAndForget by submitting pull requests.

## 🔗 Important Links

- [Releases Page](https://github.com/dawnmererighthere/FireAndForget/releases)  
- [Documentation](https://github.com/dawnmererighthere/FireAndForget/wiki)  
- [Issues](https://github.com/dawnmererighthere/FireAndForget/issues)  
- [Contributing Guidelines](https://github.com/dawnmererighthere/FireAndForget/blob/main/CONTRIBUTING.md)  

Remember, for a smooth experience, always use the latest version of FireAndForget available on our [Releases page](https://github.com/dawnmererighthere/FireAndForget/releases).