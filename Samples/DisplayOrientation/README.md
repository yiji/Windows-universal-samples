<!---
  category: ControlsLayoutAndText
  samplefwlink: http://go.microsoft.com/fwlink/p/?LinkId=624042
--->

# Display orientation sample

This sample demonstrates the use of the
[**DisplayInformation**](http://msdn.microsoft.com/library/windows/apps/dn264258)
class for retrieving the display orientation and setting an app's auto-rotation orientation preferences.

Specifically, this sample shows how to:

- Read the native display orientation.
- Read the current display orientation.
- Respond to changes in display orientation.
- Set auto-rotation orientation preferences.

This sample does not show how to adjust accelerometer data based
on the display orientation.
For a demonstration of how to perform the adjustment,
see the Orientation Changed scenario of the [the Accelerometer sample](../Accelerometer).

**Note** The Windows universal samples require Visual Studio 2015 to build and Windows 10 to execute.
 
To obtain information about Windows 10 development, go to the [Windows Dev Center](https://dev.windows.com)

To obtain information about Microsoft Visual Studio 2015 and the tools for developing Windows apps, go to [Visual Studio 2015](http://go.microsoft.com/fwlink/?LinkID=532422)

## Related topics

### Samples

[Accelerometer](../Accelerometer)

### Reference

[**Windows.Graphics.Display** namespace](http://msdn.microsoft.com/library/windows/apps/windows.graphics.display.aspx)

[**DisplayInformation** class](http://msdn.microsoft.com/library/windows/apps/dn264258)

## System requirements

**Client:** Windows 10

**Server:** Windows Server 2016 Technical Preview

**Phone:**  Windows 10

## Build the sample

1. If you download the samples ZIP, be sure to unzip the entire archive, not just the folder with the sample you want to build. 
2. Start Microsoft Visual Studio 2015 and select **File** \> **Open** \> **Project/Solution**.
3. Starting in the folder where you unzipped the samples, go to the Samples subfolder, then the subfolder for this specific sample, then the subfolder for your preferred language (C++, C#, or JavaScript). Double-click the Visual Studio 2015 Solution (.sln) file.
4. Press Ctrl+Shift+B, or select **Build** \> **Build Solution**.

## Run the sample

The next steps depend on whether you just want to deploy the sample or you want to both deploy and run it.

### Deploying the sample

- Select Build > Deploy Solution. 

### Deploying and running the sample

- To debug the sample and then run it, press F5 or select Debug >  Start Debugging. To run the sample without debugging, press Ctrl+F5 or selectDebug > Start Without Debugging. 
