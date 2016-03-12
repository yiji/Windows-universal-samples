<!---
  category: Gaming
  samplefwlink: http://go.microsoft.com/fwlink/p/?LinkId=620599
--->

# DirectX and XAML game sample

This sample demonstrates the basic end-to-end implementation of a simple first person 3-D game using DirectX (Direct3D 11.2, Direct2D, Windows.Gaming.Input, and XAudio2) and XAML in a C++ app. XAML is used for the heads-up display and game state messages.

Specifically, this sample supports:

- A touch input model
- A mouse and keyboard input model
- A game controller input model
- Stereoscopic 3-D display
- A XAML heads-up display
- A persistent game state
- Sound effect playback
- In-app purchases and trials

There are two versions of this sample:

- **Simple3DGameDX**: Uses DirectX to render game UI and implements its own layout.
- **Simple3DGameXaml**: Uses XAML to render game UI and handle layout.

Both versions share significant amounts of logic: the Common and GameContent folders are identical. In addition, to reduce disk space usage, Simple3DGameXaml references some its assets from the Simple3DGameDX\Cpp\Assets folder.

**Note** The Windows universal samples require Visual Studio 2015 to build and Windows 10 to execute.
 
To obtain information about Windows 10 development, go to the [Windows Dev Center](https://dev.windows.com)

To obtain information about Microsoft Visual Studio 2015 and the tools for developing Windows apps, go to [Visual Studio 2015](http://go.microsoft.com/fwlink/?LinkID=532422)

## Reference

This sample is written in C++ and requires some experience with graphics programming. A code walkthrough for the Direct3D-specific version of this sample is available here:

- [Create a simple  game with DirectX](https://msdn.microsoft.com/library/windows/apps/mt210793)

These topics provide info about the APIs used in this sample:

- [DirectX Graphics and Gaming](http://msdn.microsoft.com/library/windows/apps/ee663274)
- [Direct3D 11 Overview](http://msdn.microsoft.com/library/windows/apps/ff476345)
- [Direct3D 11 Reference](http://msdn.microsoft.com/library/windows/apps/ff476147)
- [DXGI reference](http://msdn.microsoft.com/library/windows/apps/bb205169)
- [XAudio2](http://msdn.microsoft.com/library/windows/apps/hh405049)
- [Windows.Gaming.Input](http://msdn.microsoft.com/library/windows/apps/windows.gaming.input)
- [Windows.UI.Xaml](http://msdn.microsoft.com/library/windows/apps/br209045)
- [Windows.UI.Xaml.Controls](http://msdn.microsoft.com/library/windows/apps/br227716)
- [Windows.UI.Xaml.Controls.SwapChainPanel](http://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.controls.swapchainpanel)

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

- To debug the sample and then run it, press F5 or select Debug >  Start Debugging. To run the sample without debugging, press Ctrl+F5 or selectDebug > Start Without Debugging. 