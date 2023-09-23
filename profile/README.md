# hyprgreen
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![Issues](https://img.shields.io/github/issues/hyprgreen/issuses?color=pink&style=plastic')](https://github.com/hyprgreen/issuses/issues)

A custom experimental [OCI](https://opencontainers.org/) [image](https://manpages.ubuntu.com/manpages/jammy/en/man5/containers-dockerfile.5.html) for [ostree-ed](https://ostreedev.github.io/ostree/) [fedora](https://fedoraproject.org/) like [silverblue](https://silverblue.fedoraproject.org/) & [kinote](https://kinoite.fedoraproject.org/) based on [ublue-os](https://github.com/ublue-os/) with the [hyprland](https://hyprland.org/) [wayland](https://wayland.freedesktop.org/) compositor.

### Notice!
```txt
Hyprgreen is in no way supported by, or a part of: Fedora project, UBlue-OS, Hyprland or any other Software or Project mentioned.
The Hyprgreen Project is Licensed under the Apache v2 License, however you may be subject to other Licenses from other software incuded.
Please read the Code of Conduct before contributing to hyprgreen, (credit to ublue-os).

Due to burnout the Hyprgreen Project is no longer in active work, updates will be slow but assuming nothing breaks it should just work (and be automaticly up-to-date) for the most part.   
```

### How to Install Hyprgreen Via Rebase
Run one of the following Commands rebase to hyprgreen: 

Main: For AMD & Intel users

[![Docker](https://github.com/hyprgreen/main/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/hyprgreen/main/actions/workflows/docker-publish.yml) ![Commit Activity](https://img.shields.io/github/commit-activity/w/hyprgreen/main?color=teal&label=Commit%20Activity&logo=github)![Latest release date](https://img.shields.io/github/release-date/hyprgreen/main?color=pink&label=Latest%20Release%20Date&logo=github)  ![Latest Tag](https://img.shields.io/github/v/tag/hyprgreen/main?color=lightblue&label=Latest%20Tag&logo=git&logoColor=lightblue&sort=semver)

Slow :
```sh
sudo rpm-ostree rebase ostree-unverified-registry:ghcr.io/hyprgreen/main:latest
```
Skate fast eat ass :
```sh
sudo rpm-ostree rebase ostree-unverified-registry:ghcr.io/hyprgreen/main:nightly
```
NVidia: For NVidia users

 [![Docker](https://github.com/hyprgreen/nvidia/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/hyprgreen/nvidia/actions/workflows/docker-publish.yml) ![Latest release date](https://img.shields.io/github/release-date/hyprgreen/nvidia?color=pink&label=Latest%20Release%20Date&logo=github) ![Latest Tag](https://img.shields.io/github/v/tag/hyprgreen/nvidia?color=lightblue&label=Latest%20Tag&logo=git&logoColor=lightblue&sort=semver)  

Slow :
```sh
sudo rpm-ostree rebase ostree-unverified-registry:ghcr.io/hyprgreen/nvidia:latest
```
Skate fast eat ass :
```sh
sudo rpm-ostree rebase ostree-unverified-registry:ghcr.io/hyprgreen/nvidia:nightly
```
( CURRENTLY IN TESTING! ) LibVirt: For AMD & Intell users That need LibVirtd

 [![Docker](https://github.com/hyprgreen/libvirt/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/hyprgreen/libvirt/actions/workflows/docker-publish.yml) ![Commit Activity](https://img.shields.io/github/commit-activity/w/hyprgreen/libvirt?color=teal&label=Commit%20Activity&logo=github) ![Latest release date](https://img.shields.io/github/release-date/hyprgreen/libvirt?color=pink&label=Latest%20Release%20Date&logo=github) ![Latest Tag](https://img.shields.io/github/v/tag/hyprgreen/libvirt?color=lightblue&label=Latest%20Tag&logo=git&logoColor=lightblue&sort=semver)  
```sh
sudo rpm-ostree rebase ostree-unverified-registry:ghcr.io/hyprgreen/libvirt:nightly
```
( CURRENTLY IN TESTING! ) LibVirt-NVidia: For NVidia users that need LibVirtd 

[![Docker](https://github.com/hyprgreen/libvirt-nvidia/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/hyprgreen/libvirt-nvidia/actions/workflows/docker-publish.yml) ![Commit Activity](https://img.shields.io/github/commit-activity/w/hyprgreen/libvirt-nvidia?color=teal&label=Commit%20Activity&logo=github) ![Latest release date](https://img.shields.io/github/release-date/hyprgreen/libvirt-nvidia?color=pink&label=Latest%20Release%20Date&logo=github) ![Latest Tag](https://img.shields.io/github/v/tag/hyprgreen/libvirt-nvidia?color=lightblue&label=Latest%20Tag&logo=git&logoColor=lightblue&sort=semver)  
```sh
sudo rpm-ostree rebase ostree-unverified-registry:ghcr.io/hyprgreen/libvirt-nvidia:nightly
```

### How we build Hyprgreen Images
https://github.com/orgs/hyprgreen/packages
![Flowchat](https://raw.githubusercontent.com/hyprgreen/.github/main/Hyprgreen-FlowChart.webp)
