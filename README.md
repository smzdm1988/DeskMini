# DeskMini Hackintosh

![Hackintosh](https://i.imgur.com/ncgwxCF.png)

### SPECS

+ OS: macOS Catalina 10.15.7 19H2 x86_64 / (SMBIOS: iMac19,1)
+ OpenCore: 0.6.3
+ CPU: Intel i5-9400 (6c6t) @ 2.90GHz
+ GPU: Intel UHD Graphics 630
+ Wi-Fi: BCM94360CS2
+ SSD: 512GB [TOSHIBA RC500 NVMe](https://union-click.jd.com/jdc?e=&p=AyIGZRprFQMTBlQeUxMEGwFdKx9KWkxYZUIeUENQDEsFA1BWThgJBABAHUBZCQUdRUFGGRJDD1MdQlUQQwVKDFRXFk8jQA4SBlQaWhAKFAFcHVMlVHdgM2koUgd3UTdBP3ZiZHoLGg0TYh4LZRprFQMTB1MeXxwGEjdlG1wlVHwHVBpaFAMTBVYSaxQyEgNcHlsdARYAURxYFzIVB1wrWxwBFQRWHV8VBhFpFCtrJQEiN2UbaxYyUGkHTAkdUBYHARhfRlIXUlBMC0AKRg9cE1oVVhUEB0kLQTIQBlQfUg%3D%3D)
+ RAM: 8GB x 2 [ADATA DDR4 2400](https://union-click.jd.com/jdc?e=&p=AyIGZRteEgYSAVEcWRQyEARSGV0RAxAFVR5rUV1KWQorAlBHU0VeBUVNR0ZbSkdETlcNVQtHRVNSUVNLXANBRA1XB14DS10cQQVYD21XHgVWHFkTBhMFVxteJUZOXRUcBEFXcl8NXxNSHBsHMEIPUnIeC2UaaxUDEwdTHl8cBhI3ZRtcJUN8B1QaWBEEEwFlGmsVBhUOVBhYFQoRAF0SaxICGzdVElgSAREBURtfFmxTN2UrWCUyIgdlGGtXbEdXBh5fQgEaAlJLDBAEFQ9cGAlFBkEPVUsMFQFCAldLaxcDEwNc)
+ Monitor: [DELL U2518D](https://union-click.jd.com/jdc?e=&p=AyIGZRtaHAAaAFUdWh0yEQZdHVoTAhsCVRhrUV1KWQorAlBHU0VeBUVNR0ZbSkdETlcNVQtHRVNSUVNLXANBRA1XB14DS10cQQVYD21XHgRUE10UBBIOUBtYJV1KRgVPGRwHcEQraAlXQE9%2FIWs9ZmIeC2UaaxUDEwdTHl8cBhI3ZRtcJUN8AVYfWhIFIgZlG18TABIPVRpTEAsQBWUcWxwyEg5WHFgWBBYHURg1VDIiN1YrayUCIgRlWTVHVxQDB0lTHAMUDlYeUhECG1IGGAkcARZTVR1dHQcSAmUZWhQGGw%3D%3D)

### TELEGRAM
[Join Telegram](https://t.me/hackintash)

### Wi-Fi CARD
My Wi-Fi card is BCM94360CS2, you need to get a NGFF card like this one. TOSHIBA RC500 NVMe SSD don't have any nand in the back, so it's very nice to have.

![BCM94360CS2](misc/BCM94360CS2.png)
![NGFF](misc/ngff.png)

### BIOS

+ Load UEFI Defaults
+ Advanced > Chipset Configuration  > Onboard HD Audio & Onboard HDMI HD Audio: Enabled
+ Advanced > Chipset Configuration  > VT-d: Disabled
+ Advanced > USB Configuration      > XHCI Hand-off: Enabled
+ Advanced > CPU Configuration      > C States Support: Disabled
+ Advanced > Super IO Configuration > Serial Port: Disabled
+ Security > Secure Boot: Disabled
+ BOOT > CSM: Enabled


### BUY ME A COFFEE
![Buy Me A Coffee](misc/WechatPay.png)

[PayPal](https://www.paypal.me/iore)

### CINEBENCH
![CINEBENCH](misc/CINEBENCH.jpg)

### TIPS
+ Change Host Name
  ```
  sudo scutil --set HostName mini
  sudo scutil --set ComputerName mini
  sudo scutil --set LocalHostName mini
  ```

### CREDITS
+ [acidanthera](https://github.com/acidanthera/OpenCorePkg)
+ [xjn819 blog](https://blog.xjn819.com/?p=7)
