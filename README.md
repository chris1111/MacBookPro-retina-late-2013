# MacBookPro-retina-late-2013



Download ➤ [EFI Monterey 12](https://github.com/chris1111/MacBookPro-retina-late-2013/raw/main/EFI%20Monterey%2012.zip) OC 0.7.8

### How to install macOS Monterey on a MacBook Pro retina late 2013
- Without patcher, without any kexts files. Genuine macOS booting with OpenCore SIP activate
- Probably work on other Mac?
- Credit: [Acidanthera](https://github.com/acidanthera/OpenCorePkg)
- For support open Issue: [New Issue](https://github.com/chris1111/MacBookPro-retina-late-2013/issues)


### If you have a mac with are you using any GPU other than the Intel Iris Pro Graphics I recommand to using [OCLP](https://dortania.github.io/OpenCore-Legacy-Patcher/)

![EFI Contents](https://user-images.githubusercontent.com/6248794/129014443-525e2366-a19f-46cf-b38c-ec15e79c8543.png)

- Looking for other OpenCore boot theme ➤ [My-Simple-OC-Themes](https://github.com/chris1111/My-Simple-OC-Themes)

### Create install Media of Monterey put the EFI folder on EFI Partition of USB installer.

### Boot from option select EFI USB install Media on the OpenCore menue Icons, select ClearNvram and Reboot the system ➣ TAB

![ClearNvram](https://user-images.githubusercontent.com/6248794/147395807-89d57034-ca2f-4704-b0a7-290bdd4338a4.png)
### Reboot
![Reboot](https://user-images.githubusercontent.com/6248794/147395810-e0e7f999-88a3-45df-a0f3-2b33e5529a14.png)

### Reboot again Option EFI USB install Media select Install macOS Monterey
![Install macOS](https://user-images.githubusercontent.com/6248794/147395808-28c6b01d-961a-4491-928f-bfa088d7fa9b.png)

### Formate the Disk then Install macOS

### Reboot again Option EFI USB install Media, select macOS Installer then complet Installation
NOTE : You have to boot multiple time on macOS Installer.


### Reboot again Option EFI USB install Media, select your Disk to complete installation
- You have to boot twice on the disk to complet
### Post Install ⬇︎
#### Mount the EFI Partition of the SSD then put the EFI Folder then unplug USB Install media

### Done! Enjoy.
### After everything is finished, you can remove the -v in the config.plist to have the apple at boot.

![Reboot MacHD](https://user-images.githubusercontent.com/6248794/147395809-f742f619-45a9-45e0-9866-b6bfc2407802.png)

<img width="1280" alt="Desktop" src="https://user-images.githubusercontent.com/6248794/128947515-28b2dd99-45b7-4074-99df-83a1b554abcf.png">

- HWMonitor
<img width="298" alt="HWM" src="https://user-images.githubusercontent.com/6248794/128948734-2c35fcd0-ca37-4526-92fd-d2bb8ab1c333.png">

### If you want make your own EFI OC I strongly advise you to compile OpenCore from source here ☞ [OpenCorePKG](https://github.com/acidanthera/OpenCorePkg)
- Use the output files in OpenCorePkg ➤ / Binaries ➤ / OpenCore-0.7.3-RELEASE.zip unzip the file and everything is there : DOC , EFI , Utilities

![Screen Shot 2021-09-03 at 7 44 10 AM](https://user-images.githubusercontent.com/6248794/132001954-96b46471-8170-4c44-a08a-94989786325a.png) 
- Read the DOC You don't need nothing else.

