<!---
  category: ControlsLayoutAndText
  samplefwlink: http://go.microsoft.com/fwlink/p/?LinkId=620520
--->

# Clipboard sample

This sample demonstrates how an app can use clipboard commands, including copy, paste, cut, and move. This sample uses classes from the [**Windows.ApplicationModel.DataTransfer**](http://msdn.microsoft.com/library/windows/apps/br205967) namespace. Some of the classes you might want to review in more detail include the [**Clipboard**](http://msdn.microsoft.com/library/windows/apps/br205867) class, which accesses the Clipboard, and the [**DataPackage**](http://msdn.microsoft.com/library/windows/apps/br205873) class, which you use to package the content before adding it to the Clipboard.

This sample covers the following:

-   How to copy and paste text
-   How to copy and paste an image
-   How to copy and paste files
-   How to get the formats on the Clipboard
-   How to detect changes to the Clipboard

**Note** The Windows universal samples require Visual Studio 2015 to build and Windows 10 to execute.
 
To obtain information about Windows 10 development, go to the [Windows Dev Center](https://dev.windows.com)

To obtain information about Microsoft Visual Studio 2015 and the tools for developing Windows apps, go to [Visual Studio 2015](http://go.microsoft.com/fwlink/?LinkID=532422)

## Related topics

### Reference

[**Clipboard**](http://msdn.microsoft.com/library/windows/apps/br205867)

[Guidelines and checklist for clipboard commands](http://msdn.microsoft.com/library/windows/apps/hh700347)

[QuickStart: Clipboard basics](http://msdn.microsoft.com/library/windows/apps/hh750308)

[**Windows.ApplicationModel.DataTransfer**](http://msdn.microsoft.com/library/windows/apps/br205967)

## System requirements

**Client:** Windows 10

**Server:** Windows Server 2016 Technical Preview

**Phone:** Windows 10

## Build the sample

1. If you download the samples ZIP, be sure to unzip the entire archive, not just the folder with the sample you want to build. 
2. Start Microsoft Visual Studio 2015 and select **File** \> **Open** \> **Project/Solution**.
3. Starting in the folder where you unzipped the samples, go to the Samples subfolder, then the subfolder for this specific sample, then the subfolder for your preferred language (C++, C#, or JavaScript). Double-click the Visual Studio 2015 Solution (.sln) file.
4. Press Ctrl+Shift+B, or select **Build** \> **Build Solution**.

## Run the sample

The next steps depend on whether you just want to deploy the sample or you want to both deploy and run it.

### Deploying the sample

- Select Build > Deploy Solution. 

### Deploying and running the sample

- To debug the sample and then run it, press F5 or select Debug >  Start Debugging. To run the sample without debugging, press Ctrl+F5 or select Debug > Start Without Debugging. 
