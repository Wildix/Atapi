# ATAPI - Managed TAPI wrapper for TAPI 2.0

forked from https://atapi.codeplex.com/

Version 1.4.0

Project Description
Managed .NET library for interacting with the Microsoft Telephony API (TAPI) 2.x. This library is for creating clients that consume telephony services on Windows XP or better.

The best way to install this into your project is through Nuget!
Right-click on the references folder in Visual Studio and select Manage Nuget Packages and type ATAPI into the search box

You can pick either 32-bit or 64-bit (note that they are different!)

This project has been around a long time on http://www.julmar.com in binary form, and I finally obtained the permission to release the full source to the project. It's very stable and has been used in all kinds of telephony related projects.

For a simple example, check out http://www.julmar.com/blog/programming/atapi-for-net-2-0/.

For more examples, download the source tree which has several test applications (https://atapi.codeplex.com/SourceControl/latest).

To use this library, it's helpful to have knowledge of TAPI as it's really just a thin wrapper over the existing API provided by Microsoft in TAPI.DLL, there's a documentation (in the form of a compiled help file for Windows) at https://atapi.codeplex.com/releases/view/106299 of the object model.