# Signing & Kernel Trust

Contributions to artifact signing, kernel module signing, and kernel trust infrastructure in VMware Photon OS.

## Kernel Trust

- [2422fe518d](https://github.com/vmware/photon/commit/2422fe518d63c20518132a405ab391438b318f7a) — `kernels: inject photon_km_2025 cert to trusted keyring`

## Signing Infrastructure - Photon Package Builder

- [f566205ced](https://github.com/vmware/photon/commit/f566205ced) — `package-builder: sign release artifacts`
- [693c4366c6](https://github.com/vmware/photon/commit/693c4366c6) — `linux, grub2, shim-signed: add network required option`
- [b9e7b29458](https://github.com/vmware/photon/commit/b9e7b2945845f62bbcc13cc03b62a93cb5c97d50) — `signer: remove explicitly mentioned script type`
- [bcd673a976](https://github.com/vmware/photon/commit/bcd673a976) — `signer: remove explicitly mentioned script type`
- [958dfc6bf3](https://github.com/vmware/photon/commit/958dfc6bf3) — `package-builder: unify dictionaries used for signing`

## Signing Infrastructure - kpatch Utility

- [7f90ffc7ef](https://github.com/vmware/photon/commit/7f90ffc7ef) — `kpatch-util: Artifacts signing for GoBuilds`
- [1da684b809](https://github.com/vmware/photon/commit/1da684b809) — `kpatch-utils: Fix find-exec issue where error from signing script is not thrown`

---

Related branch-specific commits are listed in [backport.md](./backport.md).

