# linux-pinetab2-patches

Collection of my pinetab2 patches. Descripton:
- `arm64-dts-rockchip-pinetab2-add-control-pin-to-vcc-wl.patch`: Adds power control pin to pinetab2 wifi power regulator so it can be controlled by linux kernel. At the time of writing, wifi won't work with mainline u-boot without this patch.
- `arm64-dts-rockchip-pinetab2-reduce-post-power-on-wl-delay.patch`: Reduces power-on wl delay to 15ms (from 200ms).
- `vop2-add-gamma-LUT-support.patch`: Adds gamma LUT support to VOP2
