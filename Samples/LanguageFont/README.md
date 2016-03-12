<!---
  category: GlobalizationAndLocalization
  samplefwlink: http://go.microsoft.com/fwlink/p/?LinkId=620559
--->

# Language font mapping sample

This sample demonstrates how to obtain language-specific font recommendations using the [**LanguageFontGroup**](http://msdn.microsoft.com/library/windows/apps/br206865) class in the [**Windows.Globalization.Fonts**](http://msdn.microsoft.com/library/windows/apps/br206881) namespace.

The [**LanguageFontGroup**](http://msdn.microsoft.com/library/windows/apps/br206865) APIs ([**Windows.Globalization.Fonts**](http://msdn.microsoft.com/library/windows/apps/br206881) namespace) can indicate an appropriate font to use for a given language. The caller is assumed to know the language, by whatever means; the API takes a language identifier tag and returns a recommended font. Scenarios in which this API is recommended are those that include text in multiple languages involving different character sets where a single font (even one specified in localized application resources) may not provide optimal results for all of the text. Two typical examples are:

-   An app displays notifications from external sources that might be in different languages.
-   A content-authoring app wants to pre-select recommended fonts that the user can choose in a font-picker control according to the input languages that the user has enabled.

Be aware that if the content to which the font is applied contains text that is actually in another language, the recommended font may or may not be able to support that language. If not, some text controls or frameworks that display the text might automatically select a different font during text layout as a fallback to ensure legible display.

**Note** The Windows universal samples require Visual Studio 2015 to build and Windows 10 to execute.
 
To obtain information about Windows 10 development, go to the [Windows Dev Center](https://dev.windows.com)

To obtain information about Microsoft Visual Studio 2015 and the tools for developing Windows apps, go to [Visual Studio 2015](http://go.microsoft.com/fwlink/?LinkID=532422)

## Related topics

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

