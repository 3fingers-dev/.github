# 👆👆👆 3fingers

**Prebuilt Arch Linux and NixOS virtual machine images for Apple Silicon Macs.**

The name comes from the three-finger swipe gesture which is used to switch desktops on macOS.  With 3fingers, that same gesture flips you between macOS and a full-blown Linux desktop. We've been living this workflow since the Intel/Bootcamp/VMware Fusion days over a decade ago. Now that Apple Silicon is here, 3fingers brings back the best-of-both-worlds setup with the best Linux distros and desktop environments.

## What we do

We build turnkey VM images so you can skip the lengthy, error-prone install process and go straight to a working, sensibly configured Linux desktop:

- 🐧 **Two hot distros**: Arch Linux (AArch64) and NixOS, both built for Apple Silicon
- 🖥️ **Several desktop choices**: [Niri](https://github.com/YaLTeR/niri) or [Hyprland](https://hypr.land/) (all Wayland, all tiling)
- 📦 **Your hypervisor**: VMware Fusion, UTM, and Parallels
- ⚙️ **Sensible defaults**: hotkeys, display scaling, guest tools, and the other quirks already worked out
- 🎨 **Ready to rice**: usable out of the box, designed to be customized
- 🏗️ **BYO images**: everything is built with [Packer](https://www.packer.io/) from declarative templates, so you can fork and build your own

New here? Start with **Arch Linux + Niri**. It's our default image and the smoothest landing.

## Repositories

| Repo | What it is |
|------|------------|
| [3fingers](https://github.com/3fingers-dev/3fingers) | Main repo: the Packer templates, values, and build pipeline for every image |
| [3fingers-nix](https://github.com/3fingers-dev/3fingers-nix) | NixOS configuration payload (submodule of the main repo) |
| [3fingers-ansible](https://github.com/3fingers-dev/3fingers-ansible) | Ansible post-install payload for Arch (submodule of the main repo) |
| [docs](https://github.com/3fingers-dev/docs) | User documentation, served at [3fingers.dev/docs](https://3fingers.dev/docs) |

## Links

- 🌐 Website & downloads: [3fingers.dev](https://3fingers.dev)
- 📚 Wiki: [3fingers.dev/wiki](https://3fingers.dev/wiki)
- 📺 YouTube: [@3fingers-dev](https://www.youtube.com/@3fingers-dev)

## Contributing

We welcome hardware-support reports (tell us which Apple Silicon Mac you tested on), bug fixes, new features, and documentation improvements. See the main repo's contributing guide to get started.

---

MIT licensed. Not affiliated with or endorsed by HashiCorp, Arch Linux, NixOS, VMware, UTM, or Parallels. All trademarks are the property of their respective owners.
