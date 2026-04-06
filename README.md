# Adding-custom-stamps-using-xamarin-pdf-viewer
This repository contains the sample that demonstrates adding custom stamps to a PDF using Xamarin PDF Viewer
## Overview
This repository contains a complete sample application that demonstrates how to add, apply, and preserve custom stamps in PDF documents using the Xamarin PDF Viewer across multiple platforms. The sample showcases a unified approach to implementing custom stamp annotations while maintaining platform-specific configurations for Android, iOS, and UWP.
Custom stamps are commonly used in PDF workflows to place predefined text, images, or approval marks such as Approved, Confidential, Reviewed, or organization-specific branding directly onto PDF pages. This sample illustrates how such stamps can be created programmatically and integrated into a PDF viewing and editing experience using Xamarin.
#### Platforms Covered
The solution includes separate projects for the following platforms:

Android
iOS
UWP (Universal Windows Platform)

Each platform implementation demonstrates how to interact with the Xamarin PDF Viewer control and apply custom stamp annotations consistently across devices.
#### Sample Structure
The repository contains the following key projects and files:

CustomStamps.Android – Android-specific implementation of custom PDF stamps.
CustomStamps.iOS – iOS-specific implementation of custom PDF stamps.
CustomStamps.UWP – UWP-specific implementation of custom PDF stamps.
CustomStamps – Shared code and logic used across all platforms.
CustomStamps.sln – Visual Studio solution file.
README.md – Documentation describing the sample.

### Features Demonstrated
This sample highlights the following functionalities:

Creating custom stamp annotations programmatically
Applying stamps to specific pages in a PDF document
Positioning and rendering stamps accurately within the PDF viewer
Preserving custom stamps when the PDF document is saved and reopened
Handling platform-specific initialization for Xamarin PDF Viewer
Using shared business logic with platform-specific UI handling

#### Prerequisites
Before running this sample, ensure you have the following:

Visual Studio with Xamarin development workloads installed
Windows 10 or later (for UWP development)
Android SDK and Emulator or physical Android device
macOS with Xcode installed (for iOS development)
Xamarin PDF Viewer NuGet package properly referenced in the projects

Getting Started

Clone or download this repository.
Open CustomStamps.sln in Visual Studio.
Restore NuGet packages for all projects.
Select the desired platform project (Android, iOS, or UWP) as the startup project.
Build and run the application.

When the application runs, load a PDF document and apply a custom stamp using the provided implementation. The sample demonstrates how the stamp remains embedded even after saving and reloading the PDF.
Use Cases
This sample is useful for developers who want to:

Add approval or review stamps to PDF documents
Implement document workflows in enterprise applications
Customize PDF annotation experiences in Xamarin apps
Understand cross-platform PDF annotation handling using Xamarin

## Conclusion
The Adding Custom Stamps Using Xamarin PDF Viewer sample provides a practical and extensible reference for integrating custom PDF stamps across Android, iOS, and UWP platforms. It demonstrates real-world usage of PDF annotations while maintaining code reuse and consistency through Xamarin’s shared project structure.
