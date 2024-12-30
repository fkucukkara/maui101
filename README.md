# .NET MAUI Application - 101

This is the first application in the repository, created using .NET Multi-platform App UI (MAUI). It serves as a foundational project to demonstrate the basics of building cross-platform applications using .NET MAUI.

---

## Overview

.NET MAUI (Multi-platform App UI) is a framework for building modern, native, and cross-platform applications for iOS, Android, macOS, and Windows with a single shared codebase. This project is the starting point for exploring .NET MAUI's capabilities and understanding its structure.

---

## Project Details

- **Name**: `MAUI App 101`
- **Framework**: .NET 9
- **Platforms Supported**: 
  - iOS
  - Android
  - macOS
  - Windows
- **Type**: Default template application

---

## Features

- **Cross-Platform Support**: Runs on iOS, Android, macOS, and Windows.
- **Shared UI**: A single codebase to create user interfaces and logic for all supported platforms.
- **Default MAUI Template**: The initial template includes basic navigation and UI components to get started quickly.

---

## Getting Started

Follow the steps below to set up and run the application.

### Prerequisites

1. **Install .NET SDK**:
   - Download and install the latest .NET SDK (9.0 or later) from [dotnet.microsoft.com](https://dotnet.microsoft.com/download).

2. **Install IDE**:
   - [Visual Studio 2022](https://visualstudio.microsoft.com/) (with .NET MAUI workload enabled).

3. **Platform-Specific Requirements**:
   - **Windows**: Install Windows Subsystem for Android (WSA) for running Android apps or use an emulator.
   - **macOS**: Install Xcode for iOS development.
   - **Android**: Install Android SDK and set up a device or emulator.

### Clone the Repository

```bash
git clone <repository-url>
cd <repository-directory>
```

### Build and Run

1. Open the solution file (`.sln`) in Visual Studio.
2. Select the target platform (e.g., iOS, Android, Windows).
3. Click **Run** or use the `dotnet` CLI:

```bash
# For Windows
dotnet build -f net9.0-windows10.0.19041.0

# For Android
dotnet build -f net9.0-android

# For iOS (on macOS with Xcode installed)
dotnet build -f net9.0-ios
```

4. Deploy the app to an emulator or physical device.

---

## Project Structure

- **`App.xaml`**: Contains shared application-level resources.
- **`App.xaml.cs`**: Application lifecycle and startup logic.
- **`MainPage.xaml`**: The main UI page.
- **`MainPage.xaml.cs`**: Backend logic for the main UI page.
- **`Platforms/`**: Platform-specific configurations and code for iOS, Android, macOS, and Windows.
---

## Resources

- [.NET MAUI Documentation](https://learn.microsoft.com/en-us/dotnet/maui/)
- [GitHub: .NET MAUI Samples](https://github.com/dotnet/maui-samples)
- [Microsoft Learn: .NET MAUI](https://learn.microsoft.com/en-us/training/paths/build-apps-with-dotnet-maui/)
