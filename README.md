# Hackintosh-AMD-Ryzen-5-3600-MSI-TOMAHAWK-B450-MAX
- Hi Lads
- This is the repository of my main system based on Msi B450 Tomahawk MAX.
- From this repository you can download the EFI folder

## Specs?
CPU : AMD Ryzen 5 3600 3.6 GHz 6-Core Processor
  CPU Cooler : CoolerMaster liquid cooler 240mm
 Motherboard : MSI tomahawk b450 max
      Memory : HyperX LPX 24 GB (3x 8 GB) DDR4-3200 CL16 Memory
     Storage : Toshiba  1tb HDD
     Storage : ADATA XPG SX8200 500 GB M.2-2280 NVME Solid State Drive
  Video Card : XFX Fatboy RX 590 converted to a RedDevil Powercolor RX 590 8 GB Video Card
  
## OpenCore Version?
0.6.3

## What's Working?
- [x] WIFI AirportBrcmFixup Fixed :)
- [x] Tested with macOS Mojave 10.14.6, Catalina from 10.15.4 to 10.15.7 and Big Sur Beta 6-7-8-9-10+ and Release Candidate Version 
- [x] QE/CI Graphics Of RedDevil Powercolor Radeon RX 590
- [x] Restart and Shutdown. 
- [x] Rear Jack (Green) + Front Speaker Jack (Headphone)
- [x] HDMI Audio
- [x] HDMI Output
- [x] Display Port Audio
- [x] Display Port output
- [x] HEVC and H264 Encode for RX 590
- [x] All USB ports at full speed (including USB-C)
- [x] Sleep 
- [x] Jack Mic
- [x] etc

## What's not Working?
- [ ] SideCar due to the lack of an iGPU
- [ ] etc

## Credits
- [Dortania](https://github.com/dortania) for the Opencore Desktop Guide
- [Acidanthera](https://github.com/acidanthera) for too many things to mention each, starting from Opencore bootloader to a lot of crucial kexts...
- [CorpNewt](https://github.com/corpnewt) for ProperTree and GenSMBIOS scripts
- [Trulyspinach](https://github.com/trulyspinach) for SMCAMDProcessor.kext, AMDRyzenCPUPowerManagement.kext and AMD Power Gadget app.
- [chris1111](https://github.com/chris1111) for the Opencore theme which I used in this EFI folder
- [fill0r4](https://github.com/fill0r4) for half of his entire opencore layout of 0.6.2

And to a few others to get everything working :)
