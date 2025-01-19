# ANDR_SKSEFunctions
Some native Papyrus functions in SKSE, using CommonLibSSE NG.
Originally from: https://github.com/Sacralletius/ANDR_SKSEFunctions

## Building
Run the following commands to build with CMake:
- `cmake --preset release`
- `cmake --build build/release --config Release`

Make sure that `generator` in `CMakePresets.json` is set to a tool installed on your system, like `Visual Studio 17 2022` or maybe `Ninja` for some.

## Requirements
* [CMake](https://cmake.org/)
	* Add this to your `PATH`
* [Vcpkg](https://github.com/microsoft/vcpkg)
	* Add the environment variable `VCPKG_ROOT` with the value as the path to the folder containing vcpkg
* [Visual Studio Community 2022](https://visualstudio.microsoft.com/)
	* Desktop development with C++