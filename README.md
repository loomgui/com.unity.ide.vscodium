# VSCodium Editor (`com.unity.ide.vscodium`)

A fork of Unity's [`com.unity.ide.visualstudio`](https://github.com/Unity-Technologies/com.unity.ide.visualstudio) package that adds **VSCodium** detection, alongside the existing Visual Studio and Visual Studio Code support.

## Requirements

- Unity **2021.3** or newer

## Installation

> **Important:** this package ships the same assembly (`Unity.VisualStudio.Editor`) as the official `com.unity.ide.visualstudio`. The two cannot be installed at the same time. **Remove `com.unity.ide.visualstudio` from your project first**, then add this one.

In `Packages/manifest.json`, replace the official entry with:

```jsonc
"com.unity.ide.vscodium": "https://github.com/loomgui/com.unity.ide.vscodium.git",
```

You can also use **Package Manager -> Add package from git URL** with the git URL above.

## Usage

**Preferences -> External Tools -> External Script Editor** -> select your
   VSCodium install.

## License

[`LICENSE.md`](LICENSE.md). Original work by Unity Technologies.
