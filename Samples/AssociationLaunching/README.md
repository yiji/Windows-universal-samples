<!---
  category: LaunchingAndBackgroundTasks 
  samplefwlink: http://go.microsoft.com/fwlink/p/?LinkId=620490
--->

# Association launching sample

This sample shows you how to launch an app for to handle a file type or a protocol (also known as custom scheme). You can also learn how to enable your app to be the handler for a file type or a protocol. 

**Note**  This sample was created using one of the universal app templates available in Visual Studio. For more info about how to build apps that target Windows 10 with Visual Studio, see  [Build a Windows 10 universal app using Visual Studio](http://msdn.microsoft.com/library/windows/apps/dn609832).

This sample covers these key tasks:

- launching an  app for a file using [**LaunchFileAsync**](http://msdn.microsoft.com/library/windows/apps/hh701461)
- handling file activation through the **Activated** event 
- launching an app for a protocol using [**LaunchUriAsync**](http://msdn.microsoft.com/library/windows/apps/hh701476)
- handling protocol activation through the **Activated** event 
- launching a target app and having the currently running source app remain on the screen for various amounts of screen space using [**LauncherOptions.DesiredRemainingView**](http://msdn.microsoft.com/library/windows/apps/dn298314).
- **Note**  [**LauncherOptions.DesiredRemainingView**](http://msdn.microsoft.com/library/windows/apps/dn298314) is only supported on desktop Windows when it is running in tablet mode. 

To obtain an insider copy of Windows 10, go to [Windows 10](http://insider.windows.com). 


**Note**  For Windows 10 app samples, go to  [Windows 10 Samples](https://github.com/Microsoft/Windows-universal-samples). The samples for Windows 10 can be built and run using Windows developer [tools](https://developer.windows.com).


## Related topics

- [Windows 8 app samples](http://go.microsoft.com/fwlink/p/?LinkID=227694)

### Reference
For more info about the concepts and APIs demonstrated in this sample, see these topics:

- [**Windows.ApplicationModel.Activation.FileActivatedEventArgs**](http://msdn.microsoft.com/library/windows/apps/br224716)
- [**Windows.ApplicationModel.Activation.ProtocolActivatedEventArgs**](http://msdn.microsoft.com/library/windows/apps/br224742)
- [**Windows.System.Launcher.LaunchFileAsync**](http://msdn.microsoft.com/library/windows/apps/hh701461)
- [**Windows.System.Launcher.LaunchUriAsync**](http://msdn.microsoft.com/library/windows/apps/hh701476)
- [**Windows.UI.WebUI.WebUIFileActivatedEventArgs**](http://msdn.microsoft.com/library/windows/apps/hh701781)
- [**Windows.UI.WebUI.WebUIProtocolActivatedEventArgs**](http://msdn.microsoft.com/library/windows/apps/hh701885)

###Tasks

- [Handle file activation](https://msdn.microsoft.com/library/windows/apps/mt269385)
- [Handle URI activation](https://msdn.microsoft.com/library/windows/apps/mt228339)
- [Launch the default app for a file](https://msdn.microsoft.com/library/windows/apps/mt299102)
- [Launch the default app for a URI](https://msdn.microsoft.com/library/windows/apps/mt228340)

###Guidelines

- [Guidelines and checklist for file types and protocols](http://msdn.microsoft.com/library/windows/apps/hh700321)

## System requirements

**Client:** Windows 10

**Server:** Windows Server 2016 Technical Preview

**Phone:** Windows 10

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

- To debug the sample and then run it, press F5 or select Debug >  Start Debugging. To run the sample without debugging, press Ctrl+F5 or select Debug > Start Without Debugging. 
