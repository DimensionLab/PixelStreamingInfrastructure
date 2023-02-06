# The new home for the Pixel Streaming servers!
The Pixel Streaming servers and web frontend that was in `Samples/PixelStreaming/WebServers` is now here. 

## Goals

The goals of this repository are to:

- Increase the release cadence for the Pixel Streaming servers (to mitigate browser breaking changes sooner).
- Encourage easier contribution of these components by Unreal Engine licensees.
- Facilitate a more standard web release mechanism (e.g. NPM packages or similar... coming soon).
- Grant a permissive license to distribute and modify this code wherever you see fit (MIT licensed).

## Repository contents

Reference implementations for the various pieces needed to support a PixelStreaming application:
- SignallingWebServer (Cirrus)
- SFU (Selective Forwarding Unit)
- Matchmaker

## Container images

The following container images are built from this repository:

- [ghcr.io/epicgames/pixel-streaming-signalling-server](https://github.com/orgs/EpicGames/packages/container/package/pixel-streaming-signalling-server) (since Unreal Engine 5.1)

## Versions

We maintain versions of the servers and frontend that are compatible with existing and in-development version of Unreal Engine. 

:warning: **There are breaking changes between UE versions - so make sure you get the right version**. :warning:

<ins>For a list of major changes between versions please refer to the [changelog](https://github.com/EpicGames/PixelStreamingInfrastructure/blob/master/CHANGELOG.md).</ins>

This repository contains the following in branches that track Unreal Engine versions:

[Master](https://github.com/EpicGames/PixelStreamingInfrastructure/tree/master) (This is our dev branch.)

[UE5.1 - Current](https://github.com/EpicGames/PixelStreamingInfrastructure/tree/UE5.1)

[UE5.0](https://github.com/EpicGames/PixelStreamingInfrastructure/tree/UE5.0)

[UE4.27 - End of life](https://github.com/EpicGames/PixelStreamingInfrastructure/tree/UE4.27)

[UE4.26 - Unsupported](https://github.com/EpicGames/PixelStreamingInfrastructure/tree/UE4.26)

## Legal
© 2004-2022, Epic Games, Inc. Unreal and its logo are Epic’s trademarks or registered trademarks in the US and elsewhere. 
