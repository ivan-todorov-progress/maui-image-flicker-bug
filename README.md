# Changing the ImageSource of an Image causes a noticeable flicker

This sample project demonstrates a bug in .NET MAUI when changing the ImageSource of an Image. The image is loaded asynchronously, but on Android the previous image disappears for a short time, while the new image is loading, causing a noticeable flicker. For more information see the related [.NET MAUI GitHub issue](https://github.com/dotnet/maui/issues/15501).