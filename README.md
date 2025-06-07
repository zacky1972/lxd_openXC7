# LXD configuration for openXC7 toolchain

## Usage

```bash
lxc launch ubuntu:22.04 openxc7 -c user.user-data="$(cat cloud-init.yaml)"
lxc exec openxc7 -- bash
```
