# Half Sword SDK

An auto-generated C++ SDK for Half Sword, designed to make modding and development easier. This SDK provides access to the game's classes, functions, and structures.

## Current Version

**5.4.4-2331+++Halfsword+Main-HalfswordUE5**

## Installation

### Option 1: Clone the Latest Version (Recommended)

To always get the latest SDK updates, clone as a submodule into your project:

```bash
git submodule add https://github.com/probablymeliodas/Half-Sword-SDK Half-Sword-SDK
```

To update to the latest version later:

```bash
git submodule update --remote Half-Sword-SDK
```

### Option 2: Clone a Specific Version

If you need a specific version for compatibility, you can checkout a particular tag:

```bash
# Add the submodule
git submodule add https://github.com/probablymeliodas/Half-Sword-SDK Half-Sword-SDK

# Navigate to the submodule directory
cd Half-Sword-SDK

# Checkout the specific version you need
git checkout 5.4.4-2329+++Halfsword+Main-HalfswordUE5
```

To see all available versions:

```bash
git tag -l
```

## Usage

This repository contains the contents of the `CppSDK` directory. For detailed instructions on how to use the SDK in your project, see the [official SDK documentation](https://github.com/Encryqed/Dumper-7/blob/main/UsingTheSDK.md).

## Generate Your Own SDK Dump

If you want to generate the SDK yourself (for example, after a game update):

1. Clone [Dumper-7](https://github.com/Encryqed/Dumper-7)
2. Build Dumper-7
3. Launch Half Sword
4. Inject Dumper-7 into the Half Sword process
5. Wait for the dump to complete
6. The SDK files will be saved to `C:/Dumper-7/<game version>/CppSDK`

## Contributing

If you've generated a newer version of the SDK after a game update, feel free to open a pull request or issue with the updated files.
