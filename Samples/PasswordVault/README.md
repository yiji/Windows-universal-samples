<!---
  category: IdentitySecurityAndEncryption
  samplefwlink: http://go.microsoft.com/fwlink/p/?LinkId=620583
--->

# Credential locker sample

The Credential Locker, also known as Password Vault,
provides a way for you to store user credentials (username, password) in a secure fashion for your app.
Usernames and passwords stored using the Credential Locker are encrypted and saved locally.
Once you have the credentials stored, you can automatically sign users in for a more convenient user experience.
Additionally, user credentials stored in the Credential Locker roam with the user's Microsoft Account for added convenience.
The Credential Locker can be used whether your app supports a single user accessing a single resource,
a single user accessing multiple resources,
multiple users accessing a single resource,
or
multiple users accessing multiple resources.
For more information, see the reference materials below.

This sample demonstrates the following operations:

- Saving credentials
- Reading a specific credential
- Reading all saved credentials
- Reading all saved credentials for a specific resource
- Reading all saved credentials for a specific user
- Requesting passwords from saved credentials
- Removing saved credentials

On the PC, users can manage their credentials from the desktop control panel under
User Accounts, Credential Manager.

**Note** The Windows universal samples require Visual Studio 2015 to build and Windows 10 to execute.
 
To obtain information about Windows 10 development, go to the [Windows Dev Center](https://dev.windows.com)

To obtain information about Microsoft Visual Studio 2015 and the tools for developing Windows apps, go to [Visual Studio 2015](http://go.microsoft.com/fwlink/?LinkID=532422)

## Related topics

### Samples

[**KeyCredentialManager**](../KeyCredentialManager)

### Reference

[**Storing user credentials using the Credential Locker**](https://msdn.microsoft.com/en-us/library/windows/apps/dn448950.aspx)  
[**Storing user credentials**](http://msdn.microsoft.com/library/windows/apps/hh465060)   
[**Windows.Security.Credentials** namespace](http://msdn.microsoft.com/library/windows/apps/br227089) 

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
