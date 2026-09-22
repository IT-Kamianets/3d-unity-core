# IT-Kamianets 3D Engine: Unity Core

`3d-unity-core` is the foundation package for Unity applications built on the **IT-Kamianets 3D Engine**.

It contains shared runtime infrastructure that other Unity engine packages depend on. It should remain product-independent and contain no VRoom-, racing-, or game-specific functionality.

### Logic

This package acts as the common base for:

`3d-unity-scene` → `3d-unity-assets` → `3d-unity-interaction` → `3d-unity-xr` → `3d-unity-spatial`

Its responsibility is to provide common configuration, services, lifecycle handling, events, utilities, logging, dependency access, and shared runtime abstractions.

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
