# hyprgreen

 a experimental custom fedora silverblue OCI image based on ublue-os with the hyprland wayland compositor 


### How we build Hyprgreen Images
https://github.com/orgs/hyprgreen/packages
![Flowchat](https://raw.githubusercontent.com/hyprgreen/.github/main/Hyprgreen-FlowChart.webp)


### Install Hyprgreen Via Rebase
Run one of the following Commands rebase to hyprgreen: 

Main: For AMD & Intel users
```sh
sudo rpm-ostree rebase ostree-unverified-registry:ghcr.io/hyprgreen/main:latest
```
NVidia: For NVidia users
```sh
sudo rpm-ostree rebase ostree-unverified-registry:ghcr.io/hyprgreen/nvidia:latest
```
LibVirt: For AMD & Intell users That need LibVirtd
```sh
sudo rpm-ostree rebase ostree-unverified-registry:ghcr.io/hyprgreen/libvirt:nightly
```
LibVirt-NVidia: For NVidia users that need LibVirtd
```sh
sudo rpm-ostree rebase ostree-unverified-registry:ghcr.io/hyprgreen/libvirt-nvidia:nightly
```
