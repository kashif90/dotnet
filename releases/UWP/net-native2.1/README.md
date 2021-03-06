# .NET native tools 2.1 (UWP 6.1.x) Release Notes

You can see what was included in each .NET Native 2.1 ([Microsoft.NETCore.UniversalWindowsPlatform 6.1.x](https://www.nuget.org/packages/Microsoft.NETCore.UniversalWindowsPlatform)) release below.

When using Visual Studio these packages require Visual Studio 2017 Version 15.7 or later.

### UWP 6.1.4 (.NET native tools 2.1.8) (May 7th, 2018)
- Adds support for [Optional packages with executable code](https://docs.microsoft.com/en-us/windows/uwp/packaging/optional-packages-with-executable-code)
- Fixes multiple errors caused by low memory issues when compiling .NET native apps [521825, 574099, 574102]
- Fixes Binding issues when using ReactiveUI [406415 and 406417]
- Fixes VS new project scenarios to include the correct Runtime Directives [464683]
- Fixes an issue handling unicode characters in .NET native targets [482808]
- Adds support for the Diagnostics.DisableMetadataStackTraceResolution AppContextSwitch [519008]
- Fixes crashes during compilation [525417]
- Fixes issue found when compiling complex generic types like those found in NPGSQL NuGet package [588948]
- Fixes an issue when using System.Runtime.InteropServices.SafeHandle as an argument in native to managed scenarios [601979]
