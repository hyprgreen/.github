# hyprgreen
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![Issues](https://img.shields.io/github/issues/hyprgreen/main?color=pink&style=plastic')](https://github.com/hyprgreen/main/issues)

 a experimental custom fedora silverblue OCI image based on ublue-os with the hyprland wayland compositor 


### How we build Hyprgreen Images
https://github.com/orgs/hyprgreen/packages
![Flowchat](https://raw.githubusercontent.com/hyprgreen/.github/main/Hyprgreen-FlowChart.webp)


### How to Install Hyprgreen Via Rebase
Run one of the following Commands rebase to hyprgreen: 

Main: For AMD & Intel users [![Docker](https://github.com/hyprgreen/main/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/hyprgreen/main/actions/workflows/docker-publish.yml) ![Commit Activity](https://img.shields.io/github/commit-activity/w/hyprgreen/main?color=teal&label=Commit%20Activity&logo=github)![Latest release date](https://img.shields.io/github/release-date/hyprgreen/main?color=pink&label=Latest%20Release%20Date&logo=github)  ![Latest Tag](https://img.shields.io/github/v/tag/hyprgreen/main?color=lightblue&label=Latest%20Tag&logo=git&logoColor=lightblue&sort=semver)
```sh
sudo rpm-ostree rebase ostree-unverified-registry:ghcr.io/hyprgreen/main:latest
```
NVidia: For NVidia users [![Docker](https://github.com/hyprgreen/nvidia/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/hyprgreen/nvidia/actions/workflows/docker-publish.yml) ![Latest release date](https://img.shields.io/github/release-date/hyprgreen/nvidia?color=pink&label=Latest%20Release%20Date&logo=github) ![Latest Tag](https://img.shields.io/github/v/tag/hyprgreen/nvidia?color=lightblue&label=Latest%20Tag&logo=git&logoColor=lightblue&sort=semver)  
```sh
sudo rpm-ostree rebase ostree-unverified-registry:ghcr.io/hyprgreen/nvidia:latest
```
LibVirt: For AMD & Intell users That need LibVirtd [![Docker](https://github.com/hyprgreen/libvirt/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/hyprgreen/libvirt/actions/workflows/docker-publish.yml) ![Commit Activity](https://img.shields.io/github/commit-activity/w/hyprgreen/libvirt?color=teal&label=Commit%20Activity&logo=github) ![Latest release date](https://img.shields.io/github/release-date/hyprgreen/libvirt?color=pink&label=Latest%20Release%20Date&logo=github) ![Latest Tag](https://img.shields.io/github/v/tag/hyprgreen/libvirt?color=lightblue&label=Latest%20Tag&logo=git&logoColor=lightblue&sort=semver)  
```sh
sudo rpm-ostree rebase ostree-unverified-registry:ghcr.io/hyprgreen/libvirt:nightly
```
LibVirt-NVidia: For NVidia users that need LibVirtd [![Docker](https://github.com/hyprgreen/libvirt-nvidia/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/hyprgreen/libvirt-nvidia/actions/workflows/docker-publish.yml) ![Commit Activity](https://img.shields.io/github/commit-activity/w/hyprgreen/libvirt-nvidia?color=teal&label=Commit%20Activity&logo=github) ![Latest release date](https://img.shields.io/github/release-date/hyprgreen/libvirt-nvidia?color=pink&label=Latest%20Release%20Date&logo=github) ![Latest Tag](https://img.shields.io/github/v/tag/hyprgreen/libvirt-nvidia?color=lightblue&label=Latest%20Tag&logo=git&logoColor=lightblue&sort=semver)  
```sh
sudo rpm-ostree rebase ostree-unverified-registry:ghcr.io/hyprgreen/libvirt-nvidia:nightly
```

