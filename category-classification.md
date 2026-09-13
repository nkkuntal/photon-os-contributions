# Photon OS Contribution — Category Classification

Final category assignment for the complete archive of 120 distinct Photon OS commits.

This file is the reviewed category layer. `all-commits.md` remains the authoritative complete commit dump. Related and backport commits are tracked separately in `backport.md`.

## Categories

- **Secure Boot & SBAT** — 18 commits
- **Signing & Kernel Trust** — 13 commits
- **Photon Kernel** — 33 commits
- **System & Package Security** — 43 commits
- **Photon Infrastructure & Other** — 13 commits

---

## Secure Boot & SBAT

| Date | Branch | Commit | Subject |
|---|---|---|---|
| 2025-12-22 | `5.0, 5.0-9.1.1` | [acb5bc5f1c](https://github.com/vmware/photon/commit/acb5bc5f1c) | kernels: Fix SBAT validation order |
| 2025-12-22 | `common` | [3910c8efa4](https://github.com/vmware/photon/commit/3910c8efa4) | kernels: Fix SBAT validation order |
| 2025-11-22 | `5.0, 5.0-9.1.1` | [0212e194d8](https://github.com/vmware/photon/commit/0212e194d8) | kernels: Fix SBAT validation order |
| 2025-02-28 | `common` | [e3cffb80a3](https://github.com/vmware/photon/commit/e3cffb80a3) | kernels: Port SBAT verification and kexec utilities |
| 2025-02-28 | `5.0, 5.0-9.1.1` | [d1a1480b87](https://github.com/vmware/photon/commit/d1a1480b87) | kernels: Port SBAT verification and kexec utilities |
| 2024-02-14 | `5.0, 5.0-9.1.1` | [eacedce2bb](https://github.com/vmware/photon/commit/eacedce2bb) | mokutil: version upgrade v0.7.1 |
| 2024-02-14 | `common, dev` | [d31c7a6068](https://github.com/vmware/photon/commit/d31c7a6068) | mokutil: version upgrade v0.7.1 |
| 2024-01-25 | `5.0, 5.0-9.1.1` | [199bd97541](https://github.com/vmware/photon/commit/199bd97541) | kernel: update SBAT verification |
| 2024-01-25 | `common, dev` | [001bc2b412](https://github.com/vmware/photon/commit/001bc2b412) | kernel: update SBAT verification |
| 2023-10-05 | `common, dev` | [568a9af037](https://github.com/vmware/photon/commit/568a9af037) | kernel: Kconfig to lockdown kernel in UEFI Secure Boot |
| 2023-09-30 | `common, dev` | [9e63bc7c3f](https://github.com/vmware/photon/commit/9e63bc7c3f) | mokutil: add new package |
| 2023-09-30 | `5.0, 5.0-9.1.1` | [144f45340f](https://github.com/vmware/photon/commit/144f45340f) | mokutil: add new package |
| 2023-09-28 | `4.0` | [5409fa43d9](https://github.com/vmware/photon/commit/5409fa43d9) | kernel: Kconfig to lockdown kernel in UEFI Secure Boot |
| 2023-09-27 | `5.0, 5.0-9.1.1` | [9a6115215f](https://github.com/vmware/photon/commit/9a6115215f) | kernel: Kconfig to lockdown kernel in UEFI Secure Boot |
| 2023-08-13 | `common, dev` | [a54264d066](https://github.com/vmware/photon/commit/a54264d066) | kernel: Enable KEXEC_FILE for kernel signature verification with kexec |
| 2023-08-13 | `5.0, 5.0-9.1.1` | [5948b15a64](https://github.com/vmware/photon/commit/5948b15a64) | kernel: Enable KEXEC_FILE for kernel signature verification with kexec |
| 2023-08-08 | `5.0, 5.0-9.1.1` | [e053e8161d](https://github.com/vmware/photon/commit/e053e8161d) | kernel: Enable KEXEC_FILE for kernel signature verification with kexec |
| 2023-08-08 | `common, dev` | [2774bb6849](https://github.com/vmware/photon/commit/2774bb6849) | kernel: Enable KEXEC_FILE for kernel signature verification with kexec |

## Signing & Kernel Trust

| Date | Branch | Commit | Subject |
|---|---|---|---|
| 2025-12-09 | `4.0` | [e8e60819ca](https://github.com/vmware/photon/commit/e8e60819ca) | kernels: inject photon_km_2025 cert to trusted keyring |
| 2025-11-03 | `5.0, 5.0-9.1.1` | [c45ed404e0](https://github.com/vmware/photon/commit/c45ed404e0) | kernels: inject photon_km_2025 cert to trusted keyring |
| 2025-11-03 | `common` | [80eadbaac3](https://github.com/vmware/photon/commit/80eadbaac3) | kernels: inject photon_km_2025 cert to trusted keyring |
| 2025-09-22 | `common` | [958dfc6bf3](https://github.com/vmware/photon/commit/958dfc6bf3) | package-builder: unify dictionaries used for signing |
| 2025-09-12 | `5.0, 5.0-9.1.1` | [2422fe518d](https://github.com/vmware/photon/commit/2422fe518d) | kernels: inject photon_km_2025 cert to trusted keyring |
| 2025-08-14 | `5.0, 5.0-9.1.1` | [1da684b809](https://github.com/vmware/photon/commit/1da684b809) | kpatch-utils: Fix find-exec issue where error from signing script is not thrown |
| 2025-07-30 | `common` | [bcd673a976](https://github.com/vmware/photon/commit/bcd673a976) | signer: remove explicitly mentioned script type |
| 2025-07-30 | `5.0, 5.0-9.1.1` | [9a957e60bc](https://github.com/vmware/photon/commit/9a957e60bc) | signer: remove explicitly mentioned script type |
| 2025-07-03 | `5.0, 5.0-9.1.1` | [7f90ffc7ef](https://github.com/vmware/photon/commit/7f90ffc7ef) | kpatch-util: Artifacts signing for GoBuilds |
| 2025-06-03 | `5.0, 5.0-9.1.1` | [b9e7b29458](https://github.com/vmware/photon/commit/b9e7b29458) | signer: remove explicitly mentioned script type |
| 2025-01-20 | `5.0, 5.0-9.1.1` | [693c4366c6](https://github.com/vmware/photon/commit/693c4366c6) | linux, grub2, shim-signed: add network required option |
| 2024-12-16 | `5.0, 5.0-9.1.1` | [fafaa0eb2d](https://github.com/vmware/photon/commit/fafaa0eb2d) | package-builder: sign release artifacts |
| 2024-12-16 | `common` | [f566205ced](https://github.com/vmware/photon/commit/f566205ced) | package-builder: sign release artifacts |

## Photon Kernel

| Date | Branch | Commit | Subject |
|---|---|---|---|
| 2025-12-30 | `4.0` | [ba62b1bf8e](https://github.com/vmware/photon/commit/ba62b1bf8e) | kernels: Fix CVE-2022-49444 |
| 2025-11-04 | `common` | [d5150a94af](https://github.com/vmware/photon/commit/d5150a94af) | kernels-drivers-intel-i40e: Fix CVE-2025-39901 |
| 2025-10-22 | `5.0, 5.0-9.1.1` | [b970a748df](https://github.com/vmware/photon/commit/b970a748df) | kernels: Fix CVEs |
| 2025-10-21 | `5.0, 5.0-9.1.1` | [2eb1d69e45](https://github.com/vmware/photon/commit/2eb1d69e45) | kernels: Update to v6.1.157 |
| 2025-10-02 | `5.0, 5.0-9.1.1` | [130c9bd7f6](https://github.com/vmware/photon/commit/130c9bd7f6) | kernels: Fix CVE-2024-35949 |
| 2025-09-30 | `5.0, 5.0-9.1.1` | [f737977014](https://github.com/vmware/photon/commit/f737977014) | kernels: Fix CVE-2024-38564 |
| 2025-06-19 | `5.0, 5.0-9.1.1` | [873401c8f1](https://github.com/vmware/photon/commit/873401c8f1) | kernels: Fix CVE-2024-46813 |
| 2025-06-02 | `4.0` | [c6370ef435](https://github.com/vmware/photon/commit/c6370ef435) | kernels: Fix CVE-2024-27056 |
| 2025-04-14 | `4.0` | [a5257160f5](https://github.com/vmware/photon/commit/a5257160f5) | kernels: Fix CVE-2024-26739 |
| 2025-04-08 | `4.0` | [cdb49e7b6d](https://github.com/vmware/photon/commit/cdb49e7b6d) | kernels: Fix CVE-2024-35839 |
| 2025-02-21 | `4.0` | [c0b951dfb4](https://github.com/vmware/photon/commit/c0b951dfb4) | kernels: Patch multiple CVEs |
| 2025-02-10 | `4.0` | [b91f94c61f](https://github.com/vmware/photon/commit/b91f94c61f) | kernels: Patch multiple CVEs |
| 2025-02-05 | `4.0` | [72d63d35e5](https://github.com/vmware/photon/commit/72d63d35e5) | kernels: upgrade to v5.10.234 |
| 2025-02-04 | `5.0, 5.0-9.1.1` | [eae1519771](https://github.com/vmware/photon/commit/eae1519771) | kernels: upgrade to v6.1.128 |
| 2024-10-28 | `5.0, 5.0-9.1.1` | [577a49ec7e](https://github.com/vmware/photon/commit/577a49ec7e) | linux: Fix CVE-2024-41013, CVE-2024-41014 |
| 2024-09-26 | `3.0` | [d0022b3370](https://github.com/vmware/photon/commit/d0022b3370) | kernels: upgrade to 4.19.323 |
| 2024-09-17 | `4.0` | [fe7a0c0b27](https://github.com/vmware/photon/commit/fe7a0c0b27) | linux: Fix CVE-2024-41013 and CVE-2024-41014 |
| 2024-09-10 | `4.0` | [580d86fc54](https://github.com/vmware/photon/commit/580d86fc54) | linux-generic: Fix CVE-2024-41071 |
| 2024-09-04 | `5.0, 5.0-9.1.1` | [e07f9181fa](https://github.com/vmware/photon/commit/e07f9181fa) | linux: Fix CVE-2024-41071 |
| 2024-08-15 | `5.0, 5.0-9.1.1` | [5c6c6187f2](https://github.com/vmware/photon/commit/5c6c6187f2) | linux-generic: Enable Google Virtual NIC (gVNIC) support |
| 2024-07-17 | `5.0, 5.0-9.1.1` | [d0bb90b615](https://github.com/vmware/photon/commit/d0bb90b615) | linux-generic: Keep .BTF section in modules |
| 2024-06-03 | `3.0` | [79f7af0b47](https://github.com/vmware/photon/commit/79f7af0b47) | kernel: Update to version 4.19.315, rt134 |
| 2024-05-29 | `3.0` | [f0b96a9130](https://github.com/vmware/photon/commit/f0b96a9130) | linux-rt: backport CVE-2024-26934 |
| 2024-03-29 | `4.0` | [a01aeabd3e](https://github.com/vmware/photon/commit/a01aeabd3e) | kernel: Patch fix for CVE-2024-26643 |
| 2024-03-28 | `common, dev` | [ef9a496a56](https://github.com/vmware/photon/commit/ef9a496a56) | kernel: Patch fix for CVE-2024-26643 |
| 2024-03-28 | `5.0, 5.0-9.1.1` | [8de3ee1edc](https://github.com/vmware/photon/commit/8de3ee1edc) | kernel: Patch fix for CVE-2024-26643 |
| 2024-03-21 | `3.0` | [5293bf8a03](https://github.com/vmware/photon/commit/5293bf8a03) | kernel: fix CVE-2022-48627 |
| 2023-11-02 | `common, dev` | [6c5f5e33b7](https://github.com/vmware/photon/commit/6c5f5e33b7) | kernel: Backport patches to fix CVE-2023-39191 |
| 2023-11-02 | `5.0, 5.0-9.1.1` | [65e44c618d](https://github.com/vmware/photon/commit/65e44c618d) | kernel: Backport patches to fix CVE-2023-39191 |
| 2023-10-31 | `common, dev` | [f2cf125dfa](https://github.com/vmware/photon/commit/f2cf125dfa) | kernel: Patched CVE-2023-5633 |
| 2023-10-31 | `5.0, 5.0-9.1.1` | [097313b179](https://github.com/vmware/photon/commit/097313b179) | kernel: Patched CVE-2023-5633 |
| 2023-09-06 | `3.0` | [c60473dcde](https://github.com/vmware/photon/commit/c60473dcde) | kernel: avoid TSC recalibration |
| 2023-08-04 | `4.0` | [817b8e261f](https://github.com/vmware/photon/commit/817b8e261f) | kernel: upgrade to version 5.10.188 |

## System & Package Security

| Date | Branch | Commit | Subject |
|---|---|---|---|
| 2025-12-08 | `4.0` | [6e3cfef897](https://github.com/vmware/photon/commit/6e3cfef897) | iptraf-ng: Upgrade version to fix CVE-2024-52949 |
| 2025-12-08 | `5.0, 5.0-9.1.1` | [545d2c2508](https://github.com/vmware/photon/commit/545d2c2508) | iptraf-ng: Upgrade version to fix CVE-2024-52949 |
| 2025-10-08 | `5.0, 5.0-9.1.1` | [dfc833f095](https://github.com/vmware/photon/commit/dfc833f095) | perl: Fix CVE-2025-40909 |
| 2025-10-08 | `4.0` | [5e533d69a8](https://github.com/vmware/photon/commit/5e533d69a8) | perl: Fix CVE-2025-40909 |
| 2025-04-21 | `5.0, 5.0-9.1.1` | [bfa64d3e21](https://github.com/vmware/photon/commit/bfa64d3e21) | perl: Fix CVE-2024-56406 |
| 2024-12-11 | `4.0` | [d23b79c48b](https://github.com/vmware/photon/commit/d23b79c48b) | squid: Fix CVE-2024-45802 Denial of Service processing ESI response content |
| 2024-12-11 | `3.0` | [2687f19f62](https://github.com/vmware/photon/commit/2687f19f62) | squid: Fix CVE-2024-45802 Denial of Service processing ESI response content |
| 2024-11-04 | `4.0` | [fd9903fbd9](https://github.com/vmware/photon/commit/fd9903fbd9) | apr: patch CVE-2023-49582 |
| 2024-07-17 | `5.0, 5.0-9.1.1` | [ef381f5757](https://github.com/vmware/photon/commit/ef381f5757) | nano: fix CVE-2024-5742 |
| 2024-07-09 | `5.0, 5.0-9.1.1` | [f8b19b2708](https://github.com/vmware/photon/commit/f8b19b2708) | nano: fix CVE-2024-5742 |
| 2024-02-09 | `3.0` | [915e44608f](https://github.com/vmware/photon/commit/915e44608f) | ansible: Fix CVE-2024-0690 |
| 2024-02-01 | `4.0` | [ac95e1b78c](https://github.com/vmware/photon/commit/ac95e1b78c) | ansible: fix CVE-2024-0690 |
| 2024-02-01 | `5.0, 5.0-9.1.1` | [295d8bb452](https://github.com/vmware/photon/commit/295d8bb452) | ansible: fix CVE-2024-0690 |
| 2024-01-23 | `3.0` | [a7ee511bc4](https://github.com/vmware/photon/commit/a7ee511bc4) | ansible: patched CVE-2023-5115 |
| 2023-12-11 | `5.0, 5.0-9.1.1` | [7e819837e8](https://github.com/vmware/photon/commit/7e819837e8) | perl: fix CVE-2023-47100 |
| 2023-12-11 | `4.0` | [40b659d71a](https://github.com/vmware/photon/commit/40b659d71a) | Perl: fix CVE-2023-47100 |
| 2023-11-14 | `5.0, 5.0-9.1.1` | [637930368f](https://github.com/vmware/photon/commit/637930368f) | gst-plugins-bad: Fix CVE-2023-40474 and CVE-2023-40475 |
| 2023-11-14 | `4.0` | [34262b2298](https://github.com/vmware/photon/commit/34262b2298) | gst-plugins-bad: Fix CVE-2023-40474 and CVE-2023-40475 |
| 2023-11-06 | `5.0, 5.0-9.1.1` | [3387835c07](https://github.com/vmware/photon/commit/3387835c07) | gdk-pixbuf: Fix CVE-2020-29385 |
| 2023-11-03 | `4.0` | [67d21dbec1](https://github.com/vmware/photon/commit/67d21dbec1) | gdk-pixbuf: Fix CVE-2021-44648 and CVE-2020-29385 |
| 2023-09-28 | `3.0` | [34f1a822c3](https://github.com/vmware/photon/commit/34f1a822c3) | tornado: Fix CVE-2023-28370 |
| 2023-09-21 | `5.0, 5.0-9.1.1` | [c8df18f843](https://github.com/vmware/photon/commit/c8df18f843) | libwebp: Fix invalid incremental decoding check |
| 2023-09-20 | `common, dev` | [e3d73697a5](https://github.com/vmware/photon/commit/e3d73697a5) | libwebp: version upgrade to fix CVE-2023-4863 |
| 2023-09-20 | `5.0, 5.0-9.1.1` | [aa6a96a4cc](https://github.com/vmware/photon/commit/aa6a96a4cc) | libwebp: version upgrade to fix CVE-2023-4863 |
| 2023-09-20 | `3.0` | [5ce5036766](https://github.com/vmware/photon/commit/5ce5036766) | libwebp: CVE-2023-4863 patch fix |
| 2023-09-20 | `4.0` | [07205303fc](https://github.com/vmware/photon/commit/07205303fc) | libwebp: CVE-2023-4863 patch fix |
| 2023-08-31 | `5.0, 5.0-9.1.1` | [81efc35b1b](https://github.com/vmware/photon/commit/81efc35b1b) | sqlite: Fix CVE-2023-36191 |
| 2023-08-30 | `4.0` | [455f7273ac](https://github.com/vmware/photon/commit/455f7273ac) | hwloc: handle cpuset allocation failures |
| 2023-08-30 | `5.0, 5.0-9.1.1` | [2f85e05134](https://github.com/vmware/photon/commit/2f85e05134) | hwloc: handle cpuset allocation failures |
| 2023-08-28 | `4.0` | [2856ea3229](https://github.com/vmware/photon/commit/2856ea3229) | sqlite: Fix cli segmentation fault when missing nonce |
| 2023-07-28 | `common, dev` | [fcce8a0571](https://github.com/vmware/photon/commit/fcce8a0571) | libwebp: version upgrade to fix CVE-2023-1999 |
| 2023-07-28 | `3.0` | [6e8b296647](https://github.com/vmware/photon/commit/6e8b296647) | libwebp: CVE-2023-1999 patch fix |
| 2023-07-28 | `4.0` | [546f3c9119](https://github.com/vmware/photon/commit/546f3c9119) | libwebp: CVE-2023-1999 patch fix |
| 2023-07-28 | `5.0, 5.0-9.1.1` | [48093a9943](https://github.com/vmware/photon/commit/48093a9943) | libwebp: version upgrade to fix CVE-2023-1999 |
| 2023-07-19 | `3.0` | [e02a42a261](https://github.com/vmware/photon/commit/e02a42a261) | perl: patch fix for CVE-2023-31486 and spec syntax correction according to spec check rules |
| 2023-07-18 | `5.0, 5.0-9.1.1` | [1b4964fd61](https://github.com/vmware/photon/commit/1b4964fd61) | perl: patch fix for CVE-2023-31486 |
| 2023-07-14 | `4.0` | [5293ed984d](https://github.com/vmware/photon/commit/5293ed984d) | perl: patch fix for CVE-2023-31486 |
| 2023-07-07 | `5.0, 5.0-9.1.1` | [7524d76f96](https://github.com/vmware/photon/commit/7524d76f96) | tar: CVE-2022-48303 fix |
| 2023-07-07 | `4.0` | [2cceb0e33b](https://github.com/vmware/photon/commit/2cceb0e33b) | tar: CVE-2022-48303 fix |
| 2023-06-27 | `5.0, 5.0-9.1.1` | [48f7886eae](https://github.com/vmware/photon/commit/48f7886eae) | openjdk: version bump as part of CVE-2016-7945 fix for libXi upgrade |
| 2023-06-22 | `4.0` | [d26b7f7151](https://github.com/vmware/photon/commit/d26b7f7151) | libXi: version upgrade to fix CVE-2016-7945 |
| 2023-06-21 | `common, dev` | [cc09f15918](https://github.com/vmware/photon/commit/cc09f15918) | libXi: version upgrade to fix CVE-2016-7945 |
| 2023-06-21 | `5.0, 5.0-9.1.1` | [74c10052cd](https://github.com/vmware/photon/commit/74c10052cd) | libXi: version upgrade to fix CVE-2016-7945 |

## Photon Infrastructure & Other

| Date | Branch | Commit | Subject |
|---|---|---|---|
| 2025-11-05 | `5.0, 5.0-9.1.1` | [ea839f8b40](https://github.com/vmware/photon/commit/ea839f8b40) | strace: Update to v6.18 and split into subpackage |
| 2025-10-01 | `4.0` | [85d80718f4](https://github.com/vmware/photon/commit/85d80718f4) | pyinstaller: specify minimum required dependent package versions |
| 2025-08-08 | `5.0, 5.0-9.1.1` | [c8bbd88a94](https://github.com/vmware/photon/commit/c8bbd88a94) | gst-plugins-bad: avoid illegal license |
| 2025-08-07 | `5.0, 5.0-9.1.1` | [201467b342](https://github.com/vmware/photon/commit/201467b342) | krb5: avoid illegal license |
| 2025-07-24 | `5.0, 5.0-9.1.1` | [ca4410a059](https://github.com/vmware/photon/commit/ca4410a059) | nftables, py-rust: remove files containing illegal licenses |
| 2024-12-11 | `5.0, 5.0-9.1.1` | [860cce049f](https://github.com/vmware/photon/commit/860cce049f) | squid: upgrade to v6.12 |
| 2024-10-03 | `dev` | [a1b7d7b3f3](https://github.com/vmware/photon/commit/a1b7d7b3f3) | tmux: version upgrade to v3.5 |
| 2024-10-03 | `5.0, 5.0-9.1.1` | [31292c1327](https://github.com/vmware/photon/commit/31292c1327) | tmux: version upgrade to v3.5 |
| 2024-10-02 | `5.0, 5.0-9.1.1` | [906d4c5bdd](https://github.com/vmware/photon/commit/906d4c5bdd) | nano: version upgrade to v8.2 |
| 2024-10-02 | `dev` | [0872b7c32d](https://github.com/vmware/photon/commit/0872b7c32d) | nano: version upgrade to v8.2 |
| 2024-10-01 | `4.0` | [b8d1a0ab37](https://github.com/vmware/photon/commit/b8d1a0ab37) | nano: version upgrade to v8.2 |
| 2024-09-10 | `5.0, 5.0-9.1.1` | [5be31753db](https://github.com/vmware/photon/commit/5be31753db) | apr: Upgrade version to v1.7.5 |
| 2024-06-28 | `5.0, 5.0-9.1.1` | [4deae2dbc4](https://github.com/vmware/photon/commit/4deae2dbc4) | tzdata: Upgrade package version to latest 2024a |

