<!---
  category: AudioVideoAndCamera
  samplefwlink: http://go.microsoft.com/fwlink/p/?LinkId=620571
--->

# MIDI sample

This sample demonstrates how to use the Windows.Devices.Midi API in a Windows Runtime app.

This sample demonstrates the following features:
-   Enumerate MIDI In and MIDI Out ports.
-   Attach a device watcher to monitor port arrival and removal.
-   Query the properties of a MIDI port.
-   Open MIDI In ports.
-   Open MIDI Out ports.
-   Create MIDI messages and send them to a MIDI Out ports.

## Related topics

AudioGraph, Video editing

## Operating system requirements

**Client:** Windows 10

**Server:** Windows Server 2016 Technical Preview

## Build the sample

1. If you download the samples ZIP, be sure to unzip the entire archive, not just the folder with the sample you want to build. 
2. Start Microsoft Visual Studio 2015 and select **File** \> **Open** \> **Project/Solution**.
3. Starting in the folder where you unzipped the samples, go to the Samples subfolder, then the subfolder for this specific sample, then the subfolder for your preferred language (C++, C#, or JavaScript). Double-click the Visual Studio 2015 Solution (.sln) file.
4. Press Ctrl+Shift+B, or select **Build** \> **Build Solution**.

## Run the sample

To debug the app and then run it, press F5 or use **Debug** \> **Start Debugging**. To run the app without debugging, press Ctrl+F5 or use **Debug** \> **Start Without Debugging**.

## Sounds for the MIDI synth

The sounds for the inbox MIDI GS synth are available when the Microsoft.Midi.GmDls framework package is added to the package. This SDK sample has the reference added to the project already. Note that this requires Visual Studio 2015 Update 1 [https://www.visualstudio.com/news/vs2015-update1-vs] to be installed for the appx to deploy successfully.