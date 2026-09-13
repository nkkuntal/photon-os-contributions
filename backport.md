# Backports & Related Work

Branch-specific commits related to logical changes represented in the technical category files.

Only related/backport commits are listed here. The logical commits remain in their respective category files.

## Secure Boot & SBAT

### SBAT validation order

- [3910c8efa4](https://github.com/vmware/photon/commit/3910c8efa419310d85d4299464eb0c6639d66258) | 2025-12-22 | `common` | kernels: Fix SBAT validation order
- [acb5bc5f1c](https://github.com/vmware/photon/commit/acb5bc5f1ca82ef6c11a8b38a7962111040b65c5) | 2025-12-22 | `5.0, 5.0-9.1.1` | kernels: Fix SBAT validation order

### SBAT verification / kexec utilities

- [e3cffb80a3](https://github.com/vmware/photon/commit/e3cffb80a3990eb9809ad0a8f79e354bd346ecab) | 2025-02-28 | `common` | kernels: Port SBAT verification and kexec utilities
- [2774bb6849](https://github.com/vmware/photon/commit/2774bb684911a75f698587074dfed05aca7c5d38) | 2023-08-08 | `common, dev` | kernel: Enable KEXEC_FILE for kernel signature verification with kexec
- [a54264d066](https://github.com/vmware/photon/commit/a54264d0666ae4ee169e5d5581eb0af8d3101183) | 2023-08-13 | `common, dev` | kernel: Enable KEXEC_FILE for kernel signature verification with kexec

### Kernel lockdown under UEFI Secure Boot

- [5409fa43d9](https://github.com/vmware/photon/commit/5409fa43d9ba04b877ea470adabff2370067e743) | 2023-09-28 | `4.0` | kernel: Kconfig to lockdown kernel in UEFI Secure Boot
- [568a9af037](https://github.com/vmware/photon/commit/568a9af037d38f7c0594fef126011b07bc46f8ac) | 2023-10-05 | `common, dev` | kernel: Kconfig to lockdown kernel in UEFI Secure Boot

### SBAT verification updates

- [001bc2b412](https://github.com/vmware/photon/commit/001bc2b412ae596c118a7573117700b617b73719) | 2024-01-25 | `common, dev` | kernel: update SBAT verification

### mokutil

- [d31c7a6068](https://github.com/vmware/photon/commit/d31c7a6068dcea633908cd48a2c981921685db20) | 2024-02-14 | `common, dev` | mokutil: version upgrade v0.7.1
- [9e63bc7c3f](https://github.com/vmware/photon/commit/9e63bc7c3fc574660ebc9f95598171c7f1561f08) | 2023-09-30 | `common, dev` | mokutil: add new package

## Signing & Kernel Trust

### photon_km_2025 trusted keyring

- [e8e60819ca](https://github.com/vmware/photon/commit/e8e60819ca2f47d40f559ce58dd1f7b481869d30) | 2025-12-09 | `4.0` | kernels: inject photon_km_2025 cert to trusted keyring
- [c45ed404e0](https://github.com/vmware/photon/commit/c45ed404e0e4b4508027c3d4957d54233fa5088f) | 2025-11-03 | `5.0, 5.0-9.1.1` | kernels: inject photon_km_2025 cert to trusted keyring
- [80eadbaac3](https://github.com/vmware/photon/commit/80eadbaac3cdedfe173b72164c53360e90446c62) | 2025-11-03 | `common` | kernels: inject photon_km_2025 cert to trusted keyring

### Signer script type

- [9a957e60bc](https://github.com/vmware/photon/commit/9a957e60bc597d7f41e0f7e0e093b220f82a7da9) | 2025-07-30 | `5.0, 5.0-9.1.1` | signer: remove explicitly mentioned script type

### Release artifact signing

- [fafaa0eb2d](https://github.com/vmware/photon/commit/fafaa0eb2d3712fc77e9b65e496f6d2f3202456c) | 2024-12-16 | `5.0, 5.0-9.1.1` | package-builder: sign release artifacts

## Photon Infrastructure & Other

### tmux v3.5

- [a1b7d7b3f3](https://github.com/vmware/photon/commit/a1b7d7b3f33200dd9c977a36f11e7e4732be90c1) | 2024-10-03 | `dev` | tmux: version upgrade to v3.5

### nano v8.2

- [0872b7c32d](https://github.com/vmware/photon/commit/0872b7c32db4f357f1817faa87db2e5359334a3b) | 2024-10-02 | `dev` | nano: version upgrade to v8.2
- [b8d1a0ab37](https://github.com/vmware/photon/commit/b8d1a0ab37308dfcae08c3edbb4fe63a13eb718e) | 2024-10-01 | `4.0` | nano: version upgrade to v8.2

