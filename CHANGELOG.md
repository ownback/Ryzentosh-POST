# Changelog

Format: [Keep a Changelog](https://keepachangelog.com/). Release stages: research → alpha → beta → stable.

## [Unreleased]
- Repository created from the Ryzentosh skeleton (2026-11-27).

### Changed
- Scope fixed to the owner's layout decision (2026-11-27): this repo ships the `.pkg` and installs the user-space GPU
  drivers (Metal, OpenGL, OpenCL, Vulkan, VideoToolbox) from Ryzentosh-GPU into `/Library`, signed so AMFI stays on.
  The EFI kexts and SSDTs come through Ryzentosh-EFI and Ryzentosh-ACPI.
- Dependency renamed Ryzentosh-dGPU → Ryzentosh-GPU (dGPU + iGPU).
