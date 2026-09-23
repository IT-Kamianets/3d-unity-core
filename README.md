# IT-Kamianets 3D Engine: Unity Core

`3d-unity-core` is the foundation package for Unity applications built on the **IT-Kamianets 3D Engine**.

It contains shared runtime infrastructure that other Unity engine packages depend on. It should remain product-independent and contain no VRoom-, racing-, or game-specific functionality.

### Logic

This package acts as the common base for:

`3d-unity-scene` → `3d-unity-assets` → `3d-unity-interaction` → `3d-unity-xr` → `3d-unity-spatial`

Its responsibility is to provide common configuration, services, lifecycle handling, events, utilities, logging, dependency access, and shared runtime abstractions.

### Status

Package skeleton exists: standard UPM layout (`package.json`, `Runtime/`, `Editor/`, `Tests/Runtime/`, `Tests/Editor/`, each with its own assembly definition). No runtime code yet — this just makes the package installable/referenceable by the other Unity packages in this workspace.

Package id is `com.itkamianets.3d-unity-core`. To depend on it from another Unity project, add it to that project's `Packages/manifest.json` as a [local](https://docs.unity3d.com/Manual/upm-localpath.html) or [git](https://docs.unity3d.com/Manual/upm-git.html) dependency pointing at this repo, once it has a remote.

### Roadmap

* Initial Unity package structure
* Global engine configuration
* Runtime service architecture
* Event system
* Logging and debugging
* Common interfaces and abstractions
* Shared utilities
* Package initialization lifecycle
* Error handling
* Integration with `3d-scene-schema`
* Tests and example project
* Stable v1 API
