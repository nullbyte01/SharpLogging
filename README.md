# SharpLogging
[![GitHub license](https://img.shields.io/github/license/nullbyte01/SharpLogging.svg)](https://github.com/nullbyte01/SharpLogging/blob/master/LICENSE) [![NuGet](https://img.shields.io/nuget/dt/SharpLogging.svg)](https://www.nuget.org/packages/SharperLogNet/) [![Nuget Version](https://img.shields.io/nuget/v/SharpLogging.svg)](https://www.nuget.org/packages/SharperLogNet/)

A Log library developed in C# for .NET Framework, easy to use and minimalist.
To use library either download from here or you can use NuGet Package Manager.

#### Get it from NuGet
```
Install-Package SharperLogNet -Version 1.1.0
```

Or Add Refrences by right clicking on your solution and adding references.

_CODE_
```csharp
using SharpLogging;

//you can place the code like load event in any event

 private void Window_Loaded(object sender, RoutedEventArgs e)
 {
        SharpLogging.SharpLogging sg = new SharpLogging.SharpLogging();
        sg.Logger("Test");
 }

```

By default if you dont specify path the log txt file will be saved in MyDocuments folder.

*To Specify Path use this code*
```csharp
sg.savepath = "D:\\myfolder";
```

#### Example Log ####
![Example](https://github.com/nullbyte01/SharpLogging/blob/master/1.PNG)
