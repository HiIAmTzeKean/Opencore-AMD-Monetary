# Opencore AMD Monetary

## Hardware

- CPU AMD Ryzen 5800X (8-core)
- GPU AMD RX6600
- MOBO X370 Prime
- RAM Corsair 16GB
- Seagate Firecuda 520
- Intel I211

## Software

- Monetary
- Opencore 0.9.3
- Lilu 1.6.6
- VirtualSMC 1.3.2

## Notable fix

### Mobo firmware

Firmware was udpated to the latest version. 2021 was available for my Mobo.

### Ethernet

I had issues with the latest release of ApplelGB kext. There is a legacy kext [here](https://forum.amd-osx.com/threads/intel-i211-at-alternative-to-smalltree.2028/) from Shanee which works on my machine. The kext is also uploaded in the repo.

### Issue with RTC

A workaround using AppleMCEReporterDisabler kext works well for me along with the boot-args for my GPU. I had 4G encoding enabled with CSM disabled.
