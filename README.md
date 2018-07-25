# NHLApiDotNet

A wrapper around the undocumented NHL Apis. Written in C# using [RestSharp](http://restsharp.org/).
Most underlying implementation is based off the incredible documentation and work by [Drew Hynes](https://github.com/dword4) found [here](https://github.com/dword4/nhlapi).

This code base SHOULD work on Win/Mac/*nix but I have only tested with Win10 using [.NET Core](https://dotnet.github.io/).

## Quick Notes

This is currently an incomplete implementation. Many apis documented around the web have not yet been built in here. What does exist SHOULD be working.

If there are any questions/concerns feel free to open an issue. Same goes for bugs, although for bugs I would ask you come with repro instructions to help me solve them.

## Contributing

If you would like to contribute to this repo (fix bugs, add some apis I missed etc), please fork, implement locally in your fork, ADD A TEST, and then open a PR. All help wanted and appreciated.

If you would like to change an api or DTO name, totally open to it, but please raise an issue first instead of going straight to a PR. Many of the DTOs are hastily implemented but work for my original needs.

## Known Consumers

* [JetsDiscordBot](https://github.com/joefroh/JetsDiscordBot)
