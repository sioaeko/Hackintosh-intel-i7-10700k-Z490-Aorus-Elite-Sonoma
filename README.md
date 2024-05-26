# Hackintosh-Intel-i7-10700k-AORUS-Z490-Elite-OpenCore-0.9.5
New Hackintosh portfolio for Z490 Chipset Mainboard

<img src="https://github.com/59rice/Hackintosh-Intel-i7-10700k-AORUS-Z490-Elite-OpenCore-0.9.5/assets/101755125/86aa96e4-7361-4da8-9926-a34a78ac88af" width="60%"></img>

⚠ Notice!
>We Made New EFI for compatibility MacOS Sonoma/Haeadless System
>
>it works better than 0.8.8 bootloader efi

## Hardware Spec

<img width="392" alt="스크린샷 2023-10-07 오후 9 40 18" src="https://github.com/59rice/Hackintosh-Intel-i7-10700k-AORUS-Z490-Elite-OpenCore-0.9.5/assets/101755125/0946b3b2-5be8-4119-960d-602308bd6045">

|spec|verification
|------|---
|CPU|Intel Core(R) i7-10700K
|RAM|Teamforce Xtreem RGB DDR4 16GB 4000MHz
|GPU 1| XFX Radeon RX6600XT 8GB ( Reframebuffer to AMD Radeon Pro W6600X 8GB )
|GPU 2| Intel UHD Graphics 630 ( Only FCPX acceleration/Headless )
|SSD 1| Samsung 970 Evo plus 2TB ( Hackintosh )
|SSD 2| Samsung PM981a 512GB ( Windows Dualboot )
|SMBIOS| iMac19,1

## Working Functions

<img width="1438" alt="Screenshot 2023-02-10 at 9 52 50 PM 2" src="https://user-images.githubusercontent.com/101755125/218097359-fe9371ef-6a8a-49b6-83d7-f812e9356e77.png">

|Functions|verification
|------|---
|GPU acceleration| ✓
|Wifi| ✓ - Possible to Patch Fenvi T919
|Bluetooth| ✓
|Apple Continuity| ✓ - - Possible to Patch Fenvi T919
|USB Mapping| ✓
|Sleep and wake| ✓
|2.5G Ethernet| ✓
|Intel Speedstep| ✓
|backpanel LINE OUT| ✓
|forntpanel LINE OUT| ✓


## Bios Setting

>  ⚠  Base for Aorus Z490 Elite / Master
    
    - IO Ports > Internal Graphics > ( Auto > Enabled )
    
    - IO Ports > Above 4G Decoding > ( Disabled > Enabled )
    
    - IO Ports > USB Configuration > XHCI Hand-off > ( Disabled > Enabled )
    
    - IO Ports > SATA And RST Configuration > SATA Mode Selection > ( Intel RST > AHCI )
    
    - IO Ports > Intel Platform Trust Technology ( PTT ) > ( Enabled > Disabled )
    
    - IO Ports > Software Guard Extensions ( SGX ) > ( Enabled > Disabled )
    
    - IO Ports > Trusted Computing > Security Device Support > ( Enabled > Disabled )
    
    - Boot > Boot Configuration > CFG Lock > ( Enabled > Disabled )
    
    - Boot > Boot Option Priorities > Fast Boot > Disabled Link
    
    - Boot > Boot Option Priorities > CSM Support > ( Enabled > Disabled )
    
    - Boot > Secure Boot > Secure Boot Enabled > ( Enabled > Disabled )
     
    - Keyboard F10 + Enter ( Save & Exit )

## Geekbench 6 Test

> XFX Radeon RX6600XT 8GB ( Reframebuffer to AMD Radeon Pro W6600X 8GB )
<img width="755" alt="스크린샷 2023-10-07 오후 9 35 39" src="https://github.com/59rice/Hackintosh-Intel-i7-10700k-AORUS-Z490-Elite-OpenCore-0.9.5/assets/101755125/0ab2dee6-e150-4d0e-b6bb-33a58b2c6d28">

# Intel Speed Step & Optimizing Power Management

>This EFI is perfect working new speed step and Optimizing Power Management(PM)
>
>So you don't need to use another kext or ssdt ( ex:CPUFriend/CPUFriendFriend)(SSDT-PLUG is already applied)

<img width="512" alt="스크린샷 2023-10-07 오후 9 33 53 1" src="https://github.com/59rice/Hackintosh-Intel-i7-10700k-AORUS-Z490-Elite-OpenCore-0.9.5/assets/101755125/a47c48b5-5cd9-4e10-90fa-2e6c882240bc">

## USB Port Map

<img width="2032" alt="스크린샷 2023-10-07 오후 9 35 23" src="https://github.com/59rice/Hackintosh-Intel-i7-10700k-AORUS-Z490-Elite-OpenCore-0.9.5/assets/101755125/a3b5dc0c-9b8b-42cf-8d02-08a7c0537eea">

Soon upload for usb map image to match port 

## Fenvi T919 Patch for MacOS Sonoma

> Apple had deleted the whole legacy 80211 stack on Sonoma, so you disabled old IO80211Famil.kext then replace New IO80211Family then patch to OCLP

https://www.reddit.com/r/hackintosh/comments/170q5wu/enable_wifi_in_sonoma_with_fenvi_t919/

https://github.com/5T33Z0/OC-Little-Translated/tree/main/14_OCLP_Wintel

> Thanks for zxystd,reddit,5T33Z0 :)


# Important!!

⚠ Notice!
> **If you want to use this efi normaly, Please input your New ROM / SystemUUID / SystemSerialNumber / MLB**

<img width="512" alt="Screenshot 2023-02-08 at 2 43 00 PM 1" src="https://user-images.githubusercontent.com/101755125/217446894-510dd79c-2274-491d-8599-8800ae61be68.png">

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=sioaeko/Hackintosh-Opencore-AORUS-Z490-Elite-OC-0.9.5&type=Timeline)](https://star-history.com/#sioaeko/Hackintosh-Opencore-AORUS-Z490-Elite-OC-0.9.5&Timeline)


