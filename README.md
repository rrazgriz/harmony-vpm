# Harmony VPM

![GitHub deployments](https://img.shields.io/github/deployments/rrazgriz/harmony-vpm/github-pages?label=Build%20Release)
![GitHub deployments](https://img.shields.io/github/deployments/rrazgriz/harmony-vpm/github-pages?label=Build%20Repo%20Listing)

This repo hosts a package of [Harmony](https://github.com/pardeike/Harmony) for use with the VRChat Package Manager (VPM). Harmony is a library for patching, replacing and decorating .NET and Mono methods during runtime, released under the MIT license. The harmony-vpm package is released under the same license. We use the Harmony dll built with the Net472 target.

## Installation

### Using the VRChat Package Manager

Until the VRChat Creator Companion supports user-defined repositories, you will need to manually install the package using the VPM CLI.

1. Install the [VRChat Package Manager](https://vcc.docs.vrchat.com/vpm/cli/#installation--updating).
2. Open a command prompt and enter `vpm add repo https://rrazgriz.github.io/harmony-vpm/index.json`
3. In the Creator Companion, navigate to your project and select Manage Project. Under `Selected Repos`, add the `Harmony` listing, and add the `Harmony` package to your project.

### Manual

Download the latest release from the [releases page](https://github.com/rrazgriz/harmony-vpm/releases/) and import the package into your project.
