# MacBookPro-retina-late-2013



Download ➤ [EFI Monterey 12](https://github.com/chris1111/MacBookPro-retina-late-2013/raw/main/EFI%20Monterey%2012.zip)

### How to install macOS Monterey on a MacBook Pro retina late 2013
- Without patcher, without any kexts files. Genuine macOS booting with OpenCore SIP activate
- Probably work on other Mac?
- Credit: [Acidanthera](https://github.com/acidanthera/OpenCorePkg)

### If you have a mac with are you using any GPU other than the Intel Iris Pro Graphics 
- I recommand to using [OCLP](https://dortania.github.io/OpenCore-Legacy-Patcher/)

![EFI Contents](https://user-images.githubusercontent.com/6248794/129014443-525e2366-a19f-46cf-b38c-ec15e79c8543.png)

- Looking for other OpenCore boot theme ➤ [My-Simple-OC-Themes](https://github.com/chris1111/My-Simple-OC-Themes)

### Create install Media of Monterey put the EFI folder on EFI Partition of USB installer then boot from option select EFI USB install Media on the OpenCore menue Icons, select ClearNvram and Reboot the system ➣ TAB
![ClearNvram](https://user-images.githubusercontent.com/6248794/128945677-4bf77808-147e-44c5-9a5f-d194b5ccf2a3.png)
### Reboot
![Reboot](https://user-images.githubusercontent.com/6248794/128945981-ebba5c99-3bc2-4855-8f2b-8867083c0e08.png)

### Reboot again Option EFI USB install Media select Install macOS Monterey
![Install macOS](https://user-images.githubusercontent.com/6248794/128945681-11c6034d-6d40-4349-a47a-9133cf8b7bf8.png)


### Formate the Disk then Install macOS

### Reboot again Option EFI USB install Media, select macOS Installer then complet Installation
NOTE : You have to boot multiple time on macOS Installer.


### Reboot again Option EFI USB install Media, select your Disk to complete installation
- You have to boot twice on the disk to complet
### Post Install ⬇︎
#### Mount the EFI Partition of the SSD then put the EFI Folder then unplug USB Install media

### Done! Enjoy.
### After everything is finished, you can remove the -v in the config.plist to have the apple at boot.

![Boot](https://user-images.githubusercontent.com/6248794/128947501-f810607b-d9bc-48f2-98fa-093f4474ff34.png)

<img width="1280" alt="Desktop" src="https://user-images.githubusercontent.com/6248794/128947515-28b2dd99-45b7-4074-99df-83a1b554abcf.png">

- HWMonitor
<img width="298" alt="HWM" src="https://user-images.githubusercontent.com/6248794/128948734-2c35fcd0-ca37-4526-92fd-d2bb8ab1c333.png">

### If you want make your own EFI OC I strongly advise you to compile OpenCore from source here ☞ [OpenCorePKG](https://github.com/acidanthera/OpenCorePkg)
- Use the output files in OpenCorePkg ➤ / Binaries ➤ / OpenCore-0.7.3-RELEASE.zip unzip the file and everything is there : DOC , EFI , Utilities

![Screen Shot 2021-09-03 at 7 44 10 AM](https://user-images.githubusercontent.com/6248794/132001954-96b46471-8170-4c44-a08a-94989786325a.png) 
- Read the DOC You don't need nothing else.

