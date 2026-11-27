# STATE: Ryzentosh-POST

Updated: 2026-11-27 by the docs Worker (claude-haiku-5-5 / medium), docs/layout-2026-11-27.

## Phase
Research. The skeleton exists and no work has started.

Scope fixed to the owner's layout decision (2026-11-27, DECISIONS.md "Project layout and EFI end state"): this repo
ships the `.pkg` and installs the user-space GPU drivers (Metal, OpenGL, OpenCL, Vulkan, VideoToolbox) from
Ryzentosh-GPU into `/Library`, signed so AMFI stays on. The EFI kexts and SSDTs come through Ryzentosh-EFI and
Ryzentosh-ACPI. Dependency renamed Ryzentosh-dGPU → Ryzentosh-GPU. Docs only: README, BRIEF, CLAUDE.md scope, CHANGELOG.

## In flight
Docs layout PR open from `docs/layout-2026-11-27`. Nothing else.

## Next step
The Root Orchestrator opens the first scoped issue (see the control plane's ROADMAP.md).

## Blockers
None.
