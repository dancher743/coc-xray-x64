# Changelog

All notable changes to this project will be documented in this file.

## [1.0.0] - Unreleased

### Fixes
- Fixed build errors
- Fixed rain sound after reloading a save
- Fixed Cyrillic character input in text controls
- Fixed occlusion culler buffer boundaries
- Fixed pointer-sized arguments of debugger thread-name exceptions
- Fixed thread leak and index overflow in the Resource Manager
- Fixed detection of AMD processors
- Fixed library paths in the x64 configurations for R1–R4
- Fixed handling of 64-bit region sizes and memory traversal in ptmalloc3
- Added `size` check to fix potential unsigned wrap-around on invalid size in ptmalloc3
- Fixed an unsafe conversion of the bit representation of a float in `ParticleEffect.cpp`
