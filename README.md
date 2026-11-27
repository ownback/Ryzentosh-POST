# Ryzentosh-POST

SwiftUI post-installer, updater, uninstaller, diagnostics, rollback. It ships one `.pkg`.

**What it installs:** the user-space GPU drivers that are not in the EFI: the Metal, OpenGL, OpenCL, Vulkan and
VideoToolbox bundles from [Ryzentosh-GPU](https://github.com/ownback/Ryzentosh-GPU), into `/Library`, signed so that
AMFI stays fully on.

**What it does not install:** the kexts and SSDTs. The EFI kexts (RyzentoshCPU, RyzentoshPlatform, RyzentoshWireless,
RyzentoshGPU, with Lilu and VirtualSMC) and the SSDTs from Ryzentosh-ACPI come through
[Ryzentosh-EFI](https://github.com/ownback/Ryzentosh-EFI). See the target tree in the control plane's
[EFI-END-STATE.md](https://github.com/ownback/Ryzentosh/blob/main/docs/Architecture/EFI-END-STATE.md).

Part of [Ryzentosh](https://github.com/ownback/Ryzentosh): macOS Tahoe on an AMD PC, built to behave like a Mac Apple designed and
supports. Written by AI agents. Apple is not involved in this project.

**Status:** research. Nothing here is ready to install yet. See [docs/Humans](docs/Humans/) and the
[compatibility matrix](https://github.com/ownback/Ryzentosh/blob/main/docs/Hardware/COMPATIBILITY_MATRIX.md).

**Releases:** .pkg in a .dmg.

## Reference hardware
AMD Ryzen 9 7900X3D · Radeon RX 7900 XTX (XFX) · ASUS ROG STRIX B650E-I · macOS 26.7.1 (25G241) · OpenCore 1.0.8.

## Contributing
See [CONTRIBUTING.md](https://github.com/ownback/Ryzentosh/blob/main/CONTRIBUTING.md). AI agents: read [AGENTS.md](AGENTS.md).

License: BSD-3-Clause. Third-party code and its origins are listed in [PROVENANCE.md](PROVENANCE.md).
