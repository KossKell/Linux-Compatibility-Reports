# Linux Compatibility Reports

## Purpose

This repository collects structured reports on Linux compatibility for various hardware platforms — primarily embedded boards, SBCs, and development kits. Each report documents which components work under Linux, how they were tested, and what issues were encountered.

## Scope

Reports cover the following aspects for each device:

- **Distro images**: Official and community-built distributions tested.
- **Boot / kernel / device tree**: Bootloader version, kernel version, device tree source or modifications.
- **Interfaces and drivers**: Network (Ethernet, Wi-Fi, Bluetooth), USB, storage, display, audio, camera, GPIO, and other peripherals.

## Status Vocabulary

Every item in a compatibility report uses one of the following statuses:

- **Working** — The feature operates as expected under the tested configuration.
- **Partial** — The feature works but has limitations, missing functionality, or requires workarounds.
- **Not working** — The feature does not function at all under the tested configuration.
- **Not tested** — The feature was not exercised during testing.
- **Unknown** — Insufficient information to determine status.

## Current Status

There are **no completed device reports** yet. This repository is being set up with structure, templates, and guidelines for future work.
