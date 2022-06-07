# CoreBookX-14-Hackintosh

Forked from Weachys build on 0.7.7

Made for personal use.

## Version
**OpenCore-CoreBookX14-220607** （OpenCore 0.8.1）


## Specification
- **Processor**: Intel Core i5-8259U @ 2.3GHz (Coffee Lake)
- **Graphic**: Intel® Iris® Plus Graphics 655 (共享显存 1536MB)
- **Wi-Fi**: 
   - Intel 7265  / Realtek 8821CE 
   - Broadcom BCM94360CS2 from Macbook
- **Ethernet**: No
- **Bluetooth**: 
   - Intel 7265 / Realtek 8821CE
   - Broadcom BCM94360CS2 from Macbook)
- **Audio**: Realtek ALC897 
- **Touchpad**: SYNA3602
- **Storage**: 512GB Kingston RBUSNS8154P3512GJ M.2 NVME SSD
- **TF Card Reader**: Genesys Mass Storage Device (from Genesys Logic, Inc.)
- **WebCam**: USB 2.0 Camera (from Sonix Technology Co., Ltd.)
- **USB-C**: USB Gen1 5GB/s, DP output with 4k 60hz, 45w+ PD Charging
- **Battery**: 46.2 Wh Battery

## BIOS（BIOS Settings）
- 「Advanced」-「CPU Configuration」-「Software Guard Extensions（SGX）」-「Disabled」
- 「Advanced」-「Power and Performance」- 「CPU Power Management Control」-「CPU Lock Configuration」-「CFG Lock」-「Disabled」
- 「Advanced」-「Platform Settings」-「Charging Method」-「Fast Charging」
- 「Advanced」-「AMI Graphic output Protocol Policy」-「Output Select」-「EDP1」  
   * For external display users only 
- 「Chipset」-「System Agent (SA) Configuration」-「Above 4GB MMID BIOS assignment」-「Enabled」
- 「Chipset」-「Graphics Configuration」-「DVMT Pre-Allocated」-「64MB」
- 「Boot」-「Fast Boot」-「Disabled」

## Change Log

### 2022-06-07：
1. Update OpenCore 0.8.1 + Kexts
2. Import ACPI and LID fixes from Weachy


### 2022-03-10：
1. Removed Blessoverride
2. Cleaned up config and files
3. Set APFStrim to 0


### 2022-02-19：
1. Update OpenCore 0.7.8 + Kexts
2. Removed default language