# DEPRECATED

Since Talos 1.9 is using Kernel 6.12 ther is no need to compile the 6.11 kernel, but just to add u-boot, updated repo at [https://github.com/alabruna/talos-radxa-zero-3e](https://github.com/alabruna/talos-radxa-zero-3e)


# talos-sbc-rk356x

Talos overlay for Rockchip RK356x ARM64 single-board computer (SBC) devices such as the Radxa Zero 3 series.

# Why does this exist?

Devices that uses the RK356x chipset are supported in mainline kernel since 6.11, but upstream Talos Linux uses 6.6 LTS.
U-Boot is needed for devices to correctly boot.

This project relies on the mainline U-Boot and Linux kernel and on the repository created by [Milas](https://github.com/milas/talos-sbc-rk3588)

# Device Support

* [Radxa Zero 3E](https://docs.radxa.com/en/zero/zero3?model=zero-3e)

# Install

TDB

# Machine Configuration

TBD

# Resources

* [siderolabs/talos](https://github.com/siderolabs/talos/)
* [milas/talos-sbc-rk3588](https://github.com/milas/talos-sbc-rk3588)
* [milas/rock5-talos](https://github.com/milas/rock5-talos) - forked version of Talos v1.4 using BSP kernel

# Disclaimer

This is NOT supported or endorsed by Rockchip, Radxa, Sidero Labs, or Collabora - please do not go to them with support requests!
