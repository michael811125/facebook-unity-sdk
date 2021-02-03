# Facebook SDK Package

This repository makes it possible to use [facebook-sdk-for-unity](https://github.com/facebook/facebook-sdk-for-unity) with Unity Package Manager (UPM)

## Installation

### Install via Git URL

- Add following dependency to `Packages/manifest.json` in your project;

  ```json
  {
    "dependencies": {
      "com.google.external-dependency-manager": "1.2.160",
      "com.facebook-sdk.unity": "https://github.com/unfilet/facebook-unity-sdk.git#9.0.0"
    },
    "scopedRegistries": [
    {
      "name": "Game Package Registry by Google",
      "url": "https://unityregistry-pa.googleapis.com",
      "scopes": [
        "com.google"
      ]
    }
    ]
  }
  ```

> For the official plugin, check out the [original repository](https://github.com/facebook/facebook-sdk-for-unity)
