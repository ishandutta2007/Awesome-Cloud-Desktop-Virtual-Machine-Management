# Awesome-Cloud-Desktop-Virtual-Machine-Management

# Top Cloud Desktop & Virtual Machine Management Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on Virtual Desktop Infrastructure (VDI), Browser-Based Cloud Workspaces, Hypervisor Management, Remote GPU Desktops & Containerized Desktops*  
**Last updated: November 2026**

This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Cloud Desktop & Virtual Machine Management**. These tools provision, stream, orchestrate, isolate, and manage remote Windows, Linux, and macOS virtual desktops, GPU workstations, and browser-rendered containers across enterprise VDI clouds, bare-metal hypervisors, and self-hosted homelabs.

**Examples** include Shadow PC, Paperspace Core, Amazon WorkSpaces, Microsoft Dev Box, Citrix DaaS, VMware Horizon Cloud (Omnissa Horizon), Kasm Workspaces, AppOnFly, Frame by Nutanix (Dizzion Frame), V2 Cloud, and vastsa/PI-Desktop (the category leaders and notable community entries). 

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted hypervisor management (`Proxmox VE`, `XCP-ng`, `oVirt`, `Incus`), containerized browser-streamed desktops (`KasmVNC`, `Neko`, `LinuxServer Webtop`, `Selkies-GStreamer`), clientless remote desktop gateways (`Apache Guacamole`), and lightweight desktop environments (`vastsa/PI-Desktop`) — ideal for sysadmins, DevOps engineers, cloud architects, and homelab enthusiasts.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Support & Share](#support--share)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Amazon WorkSpaces (AWS)](https://amazon.com)**  
  Fully managed, persistent cloud Virtual Desktop Infrastructure (VDI) service delivering Windows, Linux, and Ubuntu desktops with global low-latency streaming.

- **[Microsoft Dev Box & Windows 365](https://microsoft.com)**  
  Cloud-hosted developer workstations and Cloud PCs pre-configured with project repositories, IDEs, and enterprise Intune governance.

- **[Shadow PC](https://shadow.tech)**  
  High-performance cloud gaming and creative workstation service streaming dedicated Windows PCs equipped with discrete NVIDIA GPUs.

- **[Paperspace Core (DigitalOcean)](https://paperspace.com)**  
  Cloud GPU virtual machine and desktop infrastructure offering low-latency browser streaming, persistent storage, and instant Linux/Windows workstation templates.

- **[Citrix DaaS (Desktop as a Service)](https://citrix.com)**  
  Enterprise hybrid-cloud VDI platform providing HDX remote display protocols, granular security policies, and virtualized app/desktop delivery.

- **[Omnissa Horizon Cloud (formerly VMware Horizon Cloud)](https://omnissa.com)**  
  Cloud-managed VDI and published application platform scaling virtual desktops across Microsoft Azure, Amazon WorkSpaces Core, and on-premise vSphere.

- **[Dizzion Frame (formerly Frame by Nutanix)](https://dizzion.com)**  
  Browser-native Desktop-as-a-Service platform streaming GPU-accelerated Windows and Linux applications directly into HTML5 browsers without client plugins.

- **[Kasm Workspaces (Enterprise Cloud)](https://kasmweb.com)**  
  Containerized Desktop Infrastructure (CDI) platform streaming isolated browser sessions, Linux desktops, and remote Windows VMs directly to web browsers.

- **[V2 Cloud](https://v2cloud.com)**  
  All-in-one managed Desktop-as-a-Service (DaaS) solution featuring built-in cloud storage, ransomware protection, and HTML5 web-client access.

- **[AppOnFly](https://apponfly.com)**  
  Instant cloud Windows VPS and remote desktop platform accessible via browser or RDP for running Windows software on macOS, Linux, and mobile devices.


## Open-Source GitHub Projects

- **[vastsa/PI-Desktop](https://github.com)**  
  Open-source lightweight desktop and virtual/remote workspace setup utility engineered to streamline Linux desktop provisioning and remote workstation environments.

- **[Proxmox VE (`proxmox/pve-manager`)](https://github.com)**  
  Flagship open-source Type-1 server virtualization management platform combining KVM virtual machines, LXC containers, software-defined storage, and a built-in web console.

- **[Apache Guacamole (`apache/guacamole-server`)](https://github.com)**  
  Clientless open-source remote desktop gateway supporting VNC, RDP, and SSH natively in HTML5 web browsers with zero client plugins required.

- **[LinuxServer.io Webtop (`linuxserver/docker-webtop`)](https://github.com)**  
  Popular open-source Docker images delivering full Ubuntu, Alpine, Fedora, and Arch Linux desktop environments (XFCE, KDE, i3, MATE) streamed directly to web browsers via Selkies/KasmVNC.

- **[KasmVNC (`kasmtech/KasmVNC`)](https://github.com)**  
  Modern open-source web-native VNC server engineered for high-FPS, low-latency browser desktop streaming with WebP/AVIF encoding, audio pass-through, and clipboard sync.

- **[Neko (`m1k1o/neko`)](https://github.com)**  
  Self-hosted open-source virtual browser and isolated desktop environment running in Docker and streamed over WebRTC with multi-user collaborative cursor control.

- **[Selkies-GStreamer (`selkies-project/selkies-gstreamer`)](https://github.com)**  
  Open-source hardware-accelerated WebRTC remote desktop and cloud gaming streaming engine built on GStreamer for NVIDIA/VAAPI GPU workstations.

- **[Incus (`lxc/incus`)](https://github.com)**  
  Modern community-led open-source system container and virtual machine manager (forked from LXD) offering clean CLI/REST orchestration for Linux and Windows VMs.

- **[XCP-ng & Xen Orchestra (`vatesfr/xen-orchestra`)](https://github.com)**  
  Enterprise-grade open-source Xen hypervisor (`XCP-ng`) paired with a web-based management, backup, and VDI orchestration console (`Xen Orchestra`).

- **[OpenNebula (`OpenNebula/one`)](https://github.com)**  
  Turnkey open-source cloud and edge virtualization platform managing KVM virtual machines, Firecracker microVMs, and multi-tenant VDI clusters.

- **[Cockpit (`cockpit-project/cockpit`)](https://github.com)**  
  Interactive open-source web-based graphical server and virtual machine management interface (`cockpit-machines`) for Linux hosts using `libvirt` and KVM.

### Additional Strong Open-Source Options

- **[QEMU (`qemu/qemu`)](https://github.com)** and **[libvirt (`libvirt/libvirt`)](https://github.com)** for foundational open-source hardware virtualization, KVM acceleration, and cross-hypervisor management APIs.
- **[dockur/windows (`dockur/windows`)](https://github.com)** and **[dockur/macos (`dockur/macos`)](https://github.com)** for running KVM-accelerated Windows and macOS virtual machines inside Docker containers with built-in web viewers.
- **[Sunshine (`LizardByte/Sunshine`)](https://github.com)** and **[Moonlight (`moonlight-stream/moonlight-qt`)](https://github.com)** for self-hosted, ultra-low-latency 4K/120fps GPU cloud desktop and gaming streaming.
- **[RustDesk (`rustdesk/rustdesk`)](https://github.com)** for a fast, self-hostable open-source remote desktop client and relay server (TeamViewer/AnyDesk alternative).
- **[OpenUDS (`dkmaster/openuds`)](https://github.com)** for a full-featured open-source VDI connection broker supporting KVM, Proxmox, oVirt, OpenStack, RDP, and SPICE.

**Frameworks for building custom systems**: Combine **Proxmox VE** or **Incus** for VM/container orchestration, **Apache Guacamole** or **Selkies-GStreamer** for browser-based desktop streaming, and **Sunshine + Moonlight** for GPU-accelerated remote workstations.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Support & Share

If you find this curated list helpful, consider supporting the project:

- ⭐ **Star this repository** to help others discover it.
- 🍴 **Fork & Share** it with your team, friends, or community on X/Twitter, LinkedIn, and Reddit.
- ☕ **Buy me a coffee / Sponsor** my open-source work on [GitHub Sponsors](https://github.com) — featuring tiers for profile badges, README shoutouts, logo placements, and prioritized bug fixes/features!

[![Sponsor @ishandutta2007](https://shields.io)](https://github.com)

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Exposing cloud desktops, VNC/RDP gateways, or hypervisor management consoles over the public internet requires reverse proxies with HTTPS/TLS, multi-factor authentication (MFA), VPN/Zero-Trust overlays (e.g., WireGuard/Tailscale), and strict firewall rules.
- Verify operating system licensing terms (such as Microsoft Windows VDA/desktop licenses and Apple macOS EULAs) before deploying virtualized desktop infrastructure.

---

**Made for sysadmins, DevOps engineers, cloud architects, homelab builders, and open-source contributors.**  
Let's make cloud desktops and virtual machine management more open, self-hostable, and high-performance.
