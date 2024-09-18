<div align="center">

# 💻💻 OpenCore Config Files 💻💻

</div>

### OpenCore Config Files for Dell Latitude E5440

This is my second attempt at running MacOS on a non-Mac device. I had previously been able to run MacOS Catalina (10.15) on this very same device.
Note that the laptop I possess does have a dedicated graphics driver which I disabled using the `-wegnoegpu` flag in the config.plist file.

### NOTE: A lot of features have not been tested. Please use the available files at your own risk.

- #### The specs for this laptop is:
- CPU: Intel i5-4300U
- iGPU: Intel HD 4400
- dGPU: NVIDIA GT 720M (Disabled)
- RAM: 12GB (4+8 GB)
- Storage: 256 GB mSATA SSD + 320 GB HDD
- Network Wireless Card: Intel Dual Band Wireless-AC 7260

You can use the files present here, however make sure to not use them directly. Please obtain it from their respective sources, and use the respective tools found in the [Dortania Guide](https://dortania.github.io/OpenCore-Install-Guide/).

- #### Known issues (Which I will not fix):
- USB Ports (Could not get them to map properly using USBToolBox)
- Graphics Acceleration

The reason I uploaded these files on GitHub was that I was able to not only boot the MacOS installer but also install MacOS on my system successfully.

Stay chilling.
