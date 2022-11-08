# UFI & Settings - Notebook Lenovo Idealpad S145 i7-1065G7 | Intel 10th 

**Laptop Factory Defaults:**

Piece|Model
:----|:----
Plataforma|Notebook Lenovo Idealpad S145 | Intel 10th
Processador|Intel I7-1065G7
Vídeo|iGPU (integrado) Intel Iris Plus
Storage|SSD NVME 240GB for the operating system macOS
Memory|2x4GB 2667MHz DDR4, total memory 8GB 2667MHz
BIOS|Factory Default


**Upgrade of notebook:**

Piece|Model
:----|:----
Storage|SSD NVME 240GB for the operating system macOS
Additional Storage|SSD Sata 240GB for the operating system Windows
Memory|1x4GB end 1x16GB in 2667MHz DDR4, Total Memory 20GB 2667MHz
Wi-Fi Card|Fenvi Model BCM94360NG (I made an improvement I changed the default Wi-Fi card that came in the notebook. That way the Wi-Fi works natively)
Update BIOS|Version (DKCN53WW). I updated the notebook's BIOS with the Lenovo program and reconfigured some items in it


**UFI Settings:**

Options|Information
:----|:----
SMBIOS|MacBookPro16,2
macOS|See the releases and their descriptions
macOS install images|Directly from the Apple store using gibMacOS
Opencore|Version 0.7.6 the 0.8.6


- After updating the BIOS to version (DKCN53WW) and making its settings, I also modified the BIOS internally to avoid Kernel Panics!


**IMPORTANT ALERTS:**

**Observation: Carefully read the above content, because if you carefully follow everything I've done, you'll be able to use macOS without problems on your notebook, but always take into account the Hardware and Software changes I've made.

However, even with these changes made by me, it is entirely possible to adapt these EFI to your Notebook as long as it has the same Hardware version mentioned above in (Laptop Factory Defaults), it is only necessary to update and configure for the BIOS version (DKCN53WW).

I will leave just one more important detail, I removed my serials from the EFI's so it is necessary to generate new serials and add them to the config.plist file.
Use [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) to generate the serials, in order to make your life easier the place to add the serials is config.plist>PlatformInfo>Generic; and I marked the values that needed to be replaced with XXXXXXXXXXXXXXXX, just replace with the serials that you will generate in GenSMBIOS

To modify the config.plist file I use [ProperTree](https://github.com/corpnewt/ProperTree).

See photos of my Hackintosh 100% working in the previews folder.