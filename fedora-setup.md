# Installing the Radeon Proprietary Drivers

You can find the AMDGPU-PRO OpenCL driver for Fedora here: https://github.com/secureworkstation/rpm-amdgpu-pro-opencl

Additionally you can find the official drivers here: https://www.amd.com/en/support/graphics/amd-radeon-6000-series/amd-radeon-6700-series/amd-radeon-rx-6700-xt

# Install Fedy

## RPM Fusion
    sudo dnf install https://download1.rpmfusion.org/free/fedora/rpmfusion-free-release-$(rpm -E %fedora).noarch.rpm https://download1.rpmfusion.org/nonfree/fedora/rpmfusion-nonfree-release-$(rpm -E %fedora).noarch.rpm

## Install fedy copr repository
    sudo dnf copr enable kwizart/fedy

## Install fedy
    sudo dnf install fedy -y

# Install Material Shell

Github Page: https://github.com/material-shell/material-shell
Gnome Shell Extension: https://extensions.gnome.org/extension/3357/material-shell/

# Windows 10 VM Location
/var/lib/libvirt/images/win10.qcow2