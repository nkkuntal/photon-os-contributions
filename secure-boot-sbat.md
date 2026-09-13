# Secure Boot & SBAT

Contributions to Secure Boot and SBAT support in VMware Photon OS.

## Kexec in Photon

* [e053e8161d](https://github.com/vmware/photon/commit/e053e8161d) — `kernel: Enable KEXEC_FILE for kernel signature verification with kexec`
* [5948b15a64](https://github.com/vmware/photon/commit/5948b15a64) — `kernel: Enable KEXEC_FILE for kernel signature verification with kexec`

## Secure Boot Kernel Lockdown

* [9a6115215f](https://github.com/vmware/photon/commit/9a6115215f) — `kernel: Kconfig to lockdown kernel in UEFI Secure Boot`

## SBAT Validation in Kernel

* [199bd97541](https://github.com/vmware/photon/commit/199bd97541) — `kernel: update SBAT verification`
* [0212e194d8](https://github.com/vmware/photon/commit/0212e194d83dbd509f4ed8d356b33d427ce9883d) — `kernels: Fix SBAT validation order`
* [d1a1480b87](https://github.com/vmware/photon/commit/d1a1480b87) — `kernels: Port SBAT verification and kexec utilities`

## MOK / Secure Boot Userspace Support

* [144f45340f](https://github.com/vmware/photon/commit/144f45340f) — `mokutil: add new package`
* [eacedce2bb](https://github.com/vmware/photon/commit/eacedce2bb) — `mokutil: version upgrade v0.7.1`

---

Related branch-specific commits are listed in [backport.md](./backport.md).

