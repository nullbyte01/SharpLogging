# SharpLogging
A Log library developed in C# for .NET Framework, easy to use and minimalist.
To use library either download from here or you can use NuGet Package Manager.

####Get it from NuGet

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
