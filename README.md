# README

This is a simple example for creating a single-file executable console application for .NET Core. Normally, when publishing a self-contained console application with .NET Core, all the dependencies will also be included in the output folder. This is painful to distribute since it's not a single file. Currently (Aug 2018), publishing to a single-file executable is not available in the `dotnet` CLI. However, via [this initial example](https://github.com/dotnet/cli/issues/7737#issuecomment-358477509) combined with the fact that [ILCompiler is now available as a NuGet package](https://github.com/dotnet/cli/issues/7737#issuecomment-358479869), I was able to create a simple Hello World example.

Prerequisites:
 - visual studio 2017 with c++ workload

Enjoy!