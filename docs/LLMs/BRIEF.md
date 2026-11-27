# BRIEF: Ryzentosh-POST

**Scope:** SwiftUI post-installer, updater, uninstaller, diagnostics, rollback. Ships one `.pkg`, which installs the
user-space GPU drivers into `/Library`: the Metal, OpenGL, OpenCL, Vulkan and VideoToolbox bundles, signed so that AMFI
stays fully on (G-AMFI).

**Release artifact:** .pkg in a .dmg.

**Depends on:** [Ryzentosh-GPU] (dGPU + iGPU; the user-space bundles above come from it). The EFI kexts and SSDTs are
not this repo's: they come through [Ryzentosh-EFI] and [Ryzentosh-ACPI].

**Parity targets:** see the rows for this project in the control plane's COMPATIBILITY_MATRIX.md.

**Out of scope:** anything another Ryzentosh repo owns (see projects.yaml).
