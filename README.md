# dotnet_example
Full example of C# library and Python dotnet using CLR

This was harder to figure out than I thought it would be, so putting a full example in here to use/look at.


1. Create a "Class Library" project for dotnet with: `$dotnet new classlib -o Calculation`
2. Rename the `Class1.cs` to `calculate.cs` and copy the contents from this file with the _same name_ into that file.
3. Build the c# file with `dotnet build` (note the directory where you `.dll` gets placed after the build
2. Open up the `Pythondotnet_example.ipynb`, update the path to include the build directory from (1) and test out the code as specified there, it shoudl work and look sensible.


Basics of [class library](https://www.c-sharpcorner.com/UploadFile/1e050f/creating-and-using-dll-class-library-in-C-Sharp/)
Original tutorial is [here](https://github.com/pythonnet/pythonnet/wiki/How-to-call-a-dynamic-library)