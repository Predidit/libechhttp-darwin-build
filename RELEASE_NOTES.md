Precompiled dependency SDK for darwin.

- libcurl 8.22.0 with ECH enabled.
- BoringSSL cff1385e77b9b2095558fa625b3c35d589ffe09b.
- Targets: `macos-arm64`, `macos-x64`, `ios-arm64-device`, `ios-arm64-simulator`, `ios-x64-simulator`.
- Includes static libraries, matching headers, CMake imported targets, licenses,
  build metadata and SHA-256 checksums.
- Consumers compile their own bridge and statically link these dependencies.

See README.md for compiler/runtime baselines. Pin archive SHA-256 in consumers;
do not download an unpinned latest release.
