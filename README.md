# CrashExtensions

`Oxide.Ext.CrashExtensions.dll` is the extension that crash's Rust plugins run on (UI, animations, images, map rendering).

The releases here host the DLL so the `CrashExtInstaller` plugin can download it on servers whose host does not allow DLL uploads. The installer checks the exact size and sha256 of the build it was made for before it writes anything.

To install by hand instead, copy the DLL into `RustDedicated_Data/Managed` (Oxide) or `carbon/extensions` (Carbon) and restart the server.
