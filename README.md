# EFI-Gigabyte-Z490M-Gaming-X-Radeon-RX-6600

EFI para plataforma intel 10Th Gen Comet Lake


## Setup:

*  **Plataform:** Desktop Intel Core
*  **Motherboard:** Gigabyte Z490M Gaming X
*  **Storage:** SSD Samsung 970 EVO Plus 2TB
*  **Network:** Fenvi T919 BCM94360 PCIe
*  **CPU**: Intel Core i9 10900 ES 2,5 Ghz
*  **GPU:** Sapphire AMD Radeon RX 6600 8 GB
*  **RAM:** 2x16 32gb 3000 Mhz DDR4
*  **SMBios:** iMac20,2

## USBMap:
![Group](https://user-images.githubusercontent.com/99222756/206858818-cf645e86-7ab7-42b1-9991-87941b01ea11.png)

<sub>Screenshot da ferramenta Hanckintool 3.9.1 demonstrando todas as portas habilitadas neste setup </sub>

---

### ✅ USB ports Enabled: 

```
1,3,4,6,10,11,12,13,17,18,19,20,21,22,23
```
><sub>**IMPORTANTE:** Apenas 15 portas podem ser habilidatas ao mesmo tempo!</sub>

### USBmap: 

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


### Status Info: 

✅`Enabled  Port` ☑️ `Disabled Port`

# Config.plist

- `ShowPicker:` Habilita ou Desabilita o menu do OpenCore (ESC para abrir menu)
- `HideAuxiliary:` Esconder ferramentas extras do menu (Atalho Barra de espaço)
- `PollAppleHotKeys:` Habilita teclas de atalho macOS (Command+V: Verbose)

</details>