# Adding-custom-stamps-using-xamarin-pdf-viewer

This repository contains a sample application that demonstrates how to add, apply, and preserve custom stamps in PDF documents using the Xamarin PDF Viewer.

## Overview

This sample illustrates how custom stamp annotations can be implemented in a cross-platform Xamarin application. Custom stamps enable users to place predefined text, images, or approval indicators directly onto PDF pages, which is a common requirement in document review, approval, and enterprise workflows.

The repository follows a unified implementation approach while supporting platform-specific behavior for Android, iOS, and UWP.

## Supported Platforms

The sample supports the following platforms:

- Android  
- iOS  
- UWP (Universal Windows Platform)

The functionality and behavior of custom stamp annotations are consistent across all supported platforms.

## Sample Structure

The repository is organized as follows:

- **CustomStamps.Android** – Android-specific implementation  
- **CustomStamps.iOS** – iOS-specific implementation  
- **CustomStamps.UWP** – UWP-specific implementation  
- **CustomStamps** – Shared logic and common functionality  
- **CustomStamps.sln** – Visual Studio solution file  
- **README.md** – Documentation for the sample  

## Features Demonstrated

This sample showcases the following capabilities:

- Creating custom stamp annotations programmatically  
- Applying stamps to specific pages in a PDF document  
- Accurately positioning and rendering stamps within the PDF viewer  
- Preserving custom stamps when saving and reopening PDF documents  
- Using a shared codebase with platform-specific initialization  

## Prerequisites

Before running this sample, ensure you have the following:

- Visual Studio with Xamarin development workloads installed  
- Android SDK with an emulator or physical device  
- macOS with Xcode installed for iOS development  
- Windows 10 or later for UWP development  
- Xamarin PDF Viewer NuGet package referenced in all projects  

## Getting Started

1. Clone or download the repository.
2. Open `CustomStamps.sln` in Visual Studio.
3. Restore NuGet packages for all projects.
4. Set the desired platform project as the startup project.
5. Build and run the application.

Once the application is running, load a PDF document and apply a custom stamp using the implemented logic. The stamp remains embedded even after saving and reopening the document.

## Use Cases

This sample is useful for developers who want to:

- Add approval or review stamps to PDF documents  
- Implement document validation or approval workflows  
- Enhance PDF annotation capabilities in Xamarin applications  
- Understand cross-platform PDF annotation handling  

## Conclusion

The Adding Custom Stamps Using Xamarin PDF Viewer sample provides a clear reference for implementing custom stamp annotations in Xamarin applications. It demonstrates real-world usage scenarios while maintaining code reuse and consistent behavior across Android, iOS, and UWP platforms.

For more details, refer to the official Syncfusion [documentation](https://help.syncfusion.com/document-processing/pdf/pdf-viewer/xamarin/overview) and [API reference](https://help.syncfusion.com/cr/xamarin/Syncfusion.SfPdfViewer.XForms.html).
