# Changelog

All notable changes to this project will be documented in this file.

## [2.0.0] - 2026-09-26

### Added
* Runtime in-memory execution engine protection for all core shell scripts.
* Live Bind-Mount refresh and instant DNS cache flush without rebooting.
* Dedicated boot lifecycle handler (`post-fs-data.sh`) supporting Magisk, KernelSU, and APatch.
* SuSFS stealth integration with `add_try_umount` and `sus_kstat` to prevent detection.
* Fresh Daylight and Cyber-Mint WebUI design with high contrast clarity.
* Live Domain Counter showing exact active blocked domains.
* Search Region Override utility with Singapore (`gl=sg`) configuration for unrestricted results.

### Changed
* Replaced symbolic link implementation with physical hosts deployment (`0644`, SELinux context `u:object_r:system_file:s0`).
* Minified and hardened WebUI control assets.

### Fixed
* Fixed ads leaking through unmounted hosts on certain Android ROMs and kernels.
* Fixed DNS caching delay when switching protection profiles.
