﻿<!---
  category: Communications
-->

# Caller ID sample

This sample shows how to set Call Origin information for an unrecognized incoming call.

Specifically, this sample shows how to:
- Register a Caller ID background task to be triggered when an unrecognized incoming call arrives.
  The task sets the call location, category, category description, and display name of the call.
- Display the system UI to let the user choose the active Caller ID app.
- Determine whether the app is the the active Caller ID app.

See the Package.appxmanifest file for the extensions and capabilities a Caller ID app must declare.

**Note** The Windows universal samples require Visual Studio 2015 to build and Windows 10 to execute.

To obtain information about Windows 10 development, go to the [Windows Dev Center](https://dev.windows.com)

To obtain information about Microsoft Visual Studio 2015 and the tools for developing Windows apps, go to [Visual Studio 2015](http://go.microsoft.com/fwlink/?LinkID=532422)

### Reference

[Windows.ApplicationModel.Calls.Provider namespace](https://msdn.microsoft.com/en-us/library/windows/apps/windows.applicationmodel.calls.provider.aspx)

[PhoneCallOriginManager class](https://msdn.microsoft.com/en-us/library/windows/apps/windows.applicationmodel.calls.provider.phonecalloriginmanager.aspx)

[PhoneCallOrigin class](https://msdn.microsoft.com/en-us/library/windows/apps/windows.applicationmodel.calls.provider.phonecallorigin.aspx)

## System requirements

**Client:** Not Supported 

**Server:** Not Supported

**Phone:** Windows 10

## Build the sample

1. If you download the samples ZIP, be sure to unzip the entire archive, not just the folder with the sample you want to build. 
2. Start Microsoft Visual Studio 2015 and select **File** \> **Open** \> **Project/Solution**.
3. Starting in the folder where you unzipped the samples, go to the Samples subfolder, then the subfolder for this specific sample, then the subfolder for your preferred language (C++, C#, or JavaScript). Double-click the Visual Studio?2015 Solution (.sln) file.
4. Press Ctrl+Shift+B, or select **Build** \> **Build Solution**.

## Run the sample

The next steps depend on whether you just want to deploy the sample or you want to both deploy and run it.

### Deploying the sample

- Select Build > Deploy Solution. 

### Deploying and running the sample

- To debug the sample and then run it, press F5 or select Debug >  Start Debugging. To run the sample without debugging, press Ctrl+F5 or selectDebug > Start Without Debugging. 
