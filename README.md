![Plataform](https://user-images.githubusercontent.com/99222756/210241111-2f11b6c8-14be-4166-bb46-475b3c54e862.png)


Dediquei bastante tempo aprimorando e polindo esta EFI.  Portanto se de alguma forma ela te ajudar você pode me pagar um café ☕ sinta-se a vontate clicando no botão abaixo. Muito obrigado!

<a href="https://www.buymeacoffee.com/claitonllemes"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee&emoji=&slug=claitonllemes&button_colour=228636&font_colour=ffffff&font_family=Poppins&outline_colour=000000&coffee_colour=FFDD00" /></a>

![Configuration](https://user-images.githubusercontent.com/99222756/210242195-3537abf9-a0fe-4083-89d5-3723cee316a6.png)

  - #### **Plataform:** Desktop Intel Core 10Th Gen Comet Lake
  - #### **Motherboard:** Gigabyte Z490M Gaming X
  - #### **Bios Version:** F21
  - #### **Storage:** SSD Samsung 970 EVO Plus 2TB
  - #### **Network:** Fenvi T919 BCM94360 PCIe
  - #### **CPU**: Intel Core i9 10900 ES 2,5 Ghz
  - #### **GPU:** Sapphire AMD Radeon RX 6600 8 GB
  - #### **RAM:** 2x16 32gb 3000 Mhz DDR4
  - #### **SMBios:** iMac20,2 


![USBMap](https://user-images.githubusercontent.com/99222756/210242431-f6b793be-a9dc-4b1d-916e-0767d97b3ed6.png)
<details><summary>Screenshot of Hanckintool 3.9.1 with all ports enabled in this setup</summary>

<img src="https://user-images.githubusercontent.com/99222756/206858818-cf645e86-7ab7-42b1-9991-87941b01ea11.png" width="100%"/>
</details>

<details><summary>Screenshot of IOPorts map of Gigabyte Z490M Gaming X</summary> 
<img src="https://user-images.githubusercontent.com/99222756/206868553-f577f266-95fb-4549-9bdf-b020a74022b4.png" width="100%"/>
</details>

#### **USB ports Enabled:** 
```
1,3,4,6,10,11,12,13,17,18,19,20,21,22,23
```
#### **⚠️ IMPORTANT:** *Only 15 ports can be enabled at the same time!*

<br>

| Status | Connector | Port | Code | Description  | 
|:---:|:---:|:---:|:---:|---|
|✅| **USB 2.0 A** | 1 | 0 | *Port number 04*
|☑️| **USB 2.0 C** | 2 | 9 | *Port type C With Internal Switch*
|✅| **USB 2.0 A** | 3 | 0 | *Port number 01*
|✅| **USB 2.0 A** | 4 | 0 | *Port number 02*
|☑️| **USB 2.0 A** | 5 | 0 | *Port number 05*
|✅| **USB 2.0 A** | 6 | 0 | *Port number 06*
|☑️| **USB 2.0 A** | 7 | 0 | *Front Pannel - Blue*
|☑️| **USB 2.0 A** | 8 | 0 | *Unmepped*
|☑️| **USB 2.0 A** | 9 | 0 | *Unmepped*
|✅| **Internal** | 10 | 255 | *Type 3 Bluetooth USB Host Controller*
|✅| **USB 2.0 A** | 11 | 0 | *Front Pannel 01*
|✅| **USB 2.0 A** | 12 | 0 | *Front Pannel 02*
|✅| **Internal** | 13 | 255 | *Type 3 Device* 
|☑️| **USB 2.0 A** | 14 | 0 | *Unmepped*
|☑️| **USB 2.0 A** | 15 | 0 | *Unmepped*
|☑️| **USB 2.0 A** | 16 | 0 | *Unmepped*
|✅| **USB 3.0 A** | 17 | 3 | *Port number 04*
|✅| **USB 3.0 C** | 18 | 9 | *Port type C With Internal Switch*
|✅| **USB 3.0 A** | 19 | 3 | *Port number 01*
|✅| **USB 3.0 A** | 20 | 3 | *Port number 02*
|✅| **USB 3.0 A** | 21 | 3 | *Port number 05*
|✅| **USB 3.0 A** | 22 | 3 | *Port number 06*
|✅| **USB 3.0 A** | 23 | 3 | *Front Pannel - Blue*
|☑️| **USB 3.0 A** | 24 | 3 | *Unmepped*
|☑️| **USB 3.0 A** | 25 | 3 | *Unmepped*
|☑️| **USB 3.0 A** | 26 | 3 | *Unmepped*

##### **Legend:** ✅ *Enabled Port* ☑ *Disabled Port*

</details> <br>


![Important Flags](https://user-images.githubusercontent.com/99222756/210242805-2619026d-4181-41ca-904c-081b553bff43.png)

- `ShowPicker:` Habilita ou Desabilita o menu do OpenCore (ESC para abrir menu)
- `HideAuxiliary:` Esconder ferramentas extras do menu (Atalho Barra de espaço)
- `PollAppleHotKeys:` Habilita teclas de atalho macOS (Command+V: Verbose)
- `SecureBootModel:` Default (Buscar Atualizações)
- `csr-actve-config:` 00000000
  


![Bios Setup](https://user-images.githubusercontent.com/99222756/210242725-8b53ed87-278d-45b5-8017-1c724a9494b8.png)

#### **Tweaker**

- CPU Upgrade: `Gaming Profile`
- Enhanced Multi-Core Performance: `Enabled`
- Advanced CPU Settings
  - Hyper-Threading Technology: `Enabled`
  - VT-d: `Enabled`
- Extreme Memory Profile (X.M.P): `Profile1`
#### **Settings**
- Plataform Power
    - Plataform Power Management: `Enabled`
    - PCH ASPM: `Enabled`
- IO Ports
    - Internal Graphics: `Enabled`
    - Above 4G Decoding: `Enabled`
    - Re-Size BAR Support: `Disabled`
    - Super IO Configuration
        - Serial Port: `Enabled`
    - USB Configuration
        - XHCI Hand-off: `Enabled`
    - SATA And RST Configuration
        -SATA Mode Selection: `AHCI`
- Miscellaneous
    - Intel Plataform Trust Technology (PPT): `Enabled`
    - Trust Computing
        - Security Device Support: `Enabled`
#### **Boot**
- CFG Lock: `Disabled`
- Security Option: `System`
- Full Screen Logo Show: `Disabled`
- Fast Boot: `Enabled`
- CSM Support: `Disabled`
- Secure Boot
	- Secure Boot Enable: `Enabled`
	- Secure Boot Mode: `Standard`
  

![Disk Utility](https://user-images.githubusercontent.com/99222756/210242840-c34b3100-9895-4d3c-a043-09cfa6031abf.png)

#### ⚠️ IMPORTANT: 

- Connect Installer-Drive to** `USB 2.0`
- Select on menu options** `Show All Devices`  
<br>

#### Disk Format configuration:

- Name: `macOS`
- Format: `APFS`
- Scheme: `GUID Partition Map`

---
  
### **👑 Crédits:**

**Thank you all for the excellent work and dedication on this amazing project**

- ##### **Thanks to** [@acidanthera](https://github.com/acidanthera) for:

  - ###### [Opencore](https://github.com/acidanthera/OpenCorePkg) *OpenCore bootloader with development SDK*

- ##### **Thanks to** [@corpnewt](https://github.com/corpnewt) for: 

  - ###### [ProperTree](https://github.com/corpnewt/ProperTree) *A cross-platform GUI plist editor written using Python*
  - ###### [SSDTTime](https://github.com/corpnewt/SSDTTime) *A simple tool designed to make creating SSDTs simple. Supports macOS, Linux and Windows*
  - ###### [USBMap](https://github.com/corpnewt/USBMap) *Python script for mapping USB ports in macOS and creating a custom injector kext*
  - ###### [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) *Python script that uses acidanthera's macserial to generate SMBIOS and optionally saves them to a plist*
  - ###### [GibMacOS](https://github.com/corpnewt/gibMacOS) *Script that can download macOS components direct from Apple*
  - ###### [MountEFI](https://github.com/corpnewt/MountEFI) *Automatic mount EFI Script*
  - ###### [OCconfigcompare](https://github.com/corpnewt/OCConfigCompare) *Python script to compare two plists and list missing keys in either*

- ##### **Thanks to** [@luchina-gabriel](https://github.com/luchina-gabriel) for:

  - ###### [Mcrecovery](https://github.com/luchina-gabriel/macrecovery) *Tool that helps to automate recovery interaction*
  - ###### [Base EFI 10Th Gen](https://github.com/luchina-gabriel/BASE-EFI-INTEL-DESKTOP-10THGEN-COMET-LAKE) *Base EFI Intel for Comet Lake*