# freerdp_snap
Snapcraft file for the generation of xfreerdp snap package.

# Description

FreeRDP is important for "seamless" mode for running Office through Windows VM.

[Video Explanation from Level1Linux](https://www.youtube.com/watch?v=0qYf-mehpvg)

[WinApps](https://github.com/Fmstrat/winapps)

Ubuntu 20.04 has FreeRDP 2.2 package. This snapcraft file will allow to generate freerdp snap packages of newer versions.


# Build Snap Package

```
cd xfreerdp
snapcraft
```


# Package install

## note

For Winapps, to be able to mount home folder, the snap package has to be installed with classic confinement.

```
cd xfreerdp/snaps
sudo snap install xfreerdp_*_amd64.snap --dangerous --classic
```