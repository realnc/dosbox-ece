# DOSBox ECE Linux builds

[Download](https://github.com/realnc/dosbox-ece/releases/tag/latest_build)

This repository is for providing automated builds of [DOSBox
ECE](https://yesterplay.net/dosboxece/) that run on a wide variety of
Linux distributions without the need to install any of the normally
required libraries (like FluidSynth 1.x or SDL 1.2.)

To use these builds, simply mark the downloaded AppImage file as
executable and run it. On Ubuntu 22.04 or other very recent Linux
distros, you need to install libfuse2:

```text
sudo apt-get libfuse2
```

This annoyance will hopefully be fixed in the future. The AppImage devs
are working on it.
