# talos-sbc-rk356x

Talos overlay and custom kernel for Rockchip RK356x ARM64 single-board computer (SBC) devices such as the Radxa Zero 3 series.

# Why does this exist?

Currently, mainline support for the RK356x chipset is still evolving and requires a newer kernel than the 6.6 LTS available in upstream Talos Linux.
Additionally, not all patches have been merged.

This project relies on the forks of U-Boot and Linux kernel for RK356x maintained by Collabora.

# Device Support

* [Zero 3E](https://docs.radxa.com/en/zero/zero3?model=zero-3e)

# Install

TBD

# Machine Configuration

TBD

# Resources

* [Collabora RK3588 upstreaming](https://gitlab.collabora.com/hardware-enablement/rockchip-3588)
* [siderolabs/talos](https://github.com/siderolabs/talos/)
* [milas/rock5-talos](https://github.com/milas/rock5-talos) - forked version of Talos v1.4 using BSP kernel
* [milas/talos-sbc-rk3588](https://github.com/milas/talos-sbc-rk3588) - original repo this one was forked from

# Disclaimer

This is NOT supported or endorsed by Rockchip, Radxa, Sidero Labs, or Collabora - please do not go to them with support requests!
