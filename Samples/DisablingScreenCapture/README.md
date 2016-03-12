<!---
  category: IdentitySecurityAndEncryption
  samplefwlink: http://go.microsoft.com/fwlink/p/?LinkId=624047
--->

# Disabling screen capture sample

This sample shows how to disable screen capture by setting the
[**IsScreenCaptureEnabled**](http://msdn.microsoft.com/library/windows/apps/dn281123)
property of the
[**ApplicationView**](http://msdn.microsoft.com/library/windows/apps/hh701658)
object.

The sample consists of the following scenarios:

- Allow screen capture by taking no special action. Screen capture is allowed by default.
- Blocking screen capture for a specific page
  by setting [**IsScreenCaptureEnabled**](http://msdn.microsoft.com/library/windows/apps/dn281123)
  to **false** when the user navigates to the page, then setting it back to **true** when the user navigates away.

**Note** The Windows universal samples require Visual Studio 2015 to build and Windows 10 to execute.
 
To obtain information about Windows 10 development, go to the [Windows Dev Center](https://dev.windows.com)

To obtain information about Microsoft Visual Studio 2015 and the tools for developing Windows apps, go to [Visual Studio 2015](http://go.microsoft.com/fwlink/?LinkID=532422)

## Related topics

### Reference

[ApplicationView class](https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.viewmanagement.applicationview.aspx)

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
