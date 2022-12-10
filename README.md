# EFI-Gigabyte-Z490M-Gaming-X-Radeon-RX-6600

EFI para plataforma intel 10Th Gen Comet Lake


### Setup:

- [X] Plataforma: Desktop | Intel Core
- [x] Placa Mãe: Gigabyte Z490M Gaming X
- [x] SSD: Samsung 970 EVO Plus 2TB
- [x] Network: Fenvi T919 BCM94360 PCIe
- [x] Processador: Intel Core i9 10900 ES 2,5 Ghz 
- [x] RAM: 2x16 32gb 3000 Mhz DDR4
- [x] Vídeo: Sapphire AMD Radeon RX 6600 8 GB
- [x] SMBIOS: iMac20,2

### USBMap:

![Group 1](https://user-images.githubusercontent.com/99222756/206858818-cf645e86-7ab7-42b1-9991-87941b01ea11.png)

<sub>Screenshot da ferramenta Hanckintool 3.9.1 demonstrando todas as portas habilitadas neste setup </sub>


- [x] USB ports Enabled: 
> Only 15 Ports Support

```
1,2,3,4,6,10,11,12,13,17,19,20,21,22,23
```

## Internal [255]

- [x] 13. UK13 | AppleUSB20XHCIPort | 13 (0d000000) | 14d00000 | Type 3 Device
- [x] 10. UK10 | AppleUSB20XHCIPort | 10 (0a000000) | 14a00000 | Type 3 Bluetooth USB Host Controller

```
T: 10,13:255
```
<details><summary>USB 2.0 Type A</summary>

<p>
## USB3.0-TypeA [3]

- [x] 01. UK01 | AppleUSB20XHCIPort | 01 (01000000) | 14100000 | Type 3 // Porta 04
- [x] 03. UK03 | AppleUSB20XHCIPort | 03 (03000000) | 14300000 | Type 3 // Porta 01
- [x] 04. UK04 | AppleUSB20XHCIPort | 04 (04000000) | 14400000 | Type 3 // Porta 02
- [ ] 05. UK05 | AppleUSB20XHCIPort | 05 (05000000) | 14500000 | Type 3 // Porta 05
- [x] 06. UK06 | AppleUSB20XHCIPort | 06 (06000000) | 14600000 | Type 3 // Porta 06
- [ ] 07. UK07 | AppleUSB20XHCIPort | 07 (07000000) | 14700000 | Type 3 // Painel Frontal (azul)
- [ ] 08. UK08 | AppleUSB20XHCIPort | 08 (08000000) | 14800000 | Type 3 // Unmepped
- [ ] 09. UK09 | AppleUSB20XHCIPort | 09 (09000000) | 14900000 | Type 3 // Unmepped
- [x] 11. UK11 | AppleUSB20XHCIPort | 11 (0b000000) | 14b00000 | Type 3 // Painel Frontal (ao lado da Azul)
- [x] 12. UK12 | AppleUSB20XHCIPort | 12 (0c000000) | 14c00000 | Type 3 // Painel Frontal
- [x] 14. UK14 | AppleUSB20XHCIPort | 14 (0e000000) | 14e00000 | Type 3 // Unmepped
- [ ] 15. UK15 | AppleUSB20XHCIPort | 15 (0f000000) | 14f00000 | Type 3 // Unmepped
- [ ] 16. UK16 | AppleUSB20XHCIPort | 16 (10000000) | 14000000 | Type 3 // Unmepped

</p></details>

## USB3.0-TypeA [3]

- [x] 17. UK17 | AppleUSB30XHCIPort | 17 (11000000) | 14100000 | Type 3 // Porta 04
- [x] 19. UK19 | AppleUSB30XHCIPort | 19 (13000000) | 14300000 | Type 3 // Porta 01
- [x] 20. UK20 | AppleUSB30XHCIPort | 20 (14000000) | 14400000 | Type 3 // Porta 02
- [x] 21. UK21 | AppleUSB30XHCIPort | 21 (15000000) | 14500000 | Type 3 // Porta 05
- [x] 22. UK22 | AppleUSB30XHCIPort | 22 (16000000) | 14600000 | Type 3 // Porta 06
- [x] 23. UK23 | AppleUSB30XHCIPort | 23 (17000000) | 14700000 | Type 3 // Painel Frontal 01 (azul)
- [ ] 24. UK24 | AppleUSB30XHCIPort | 24 (18000000) | 14800000 | Type 3 // Unmepped
- [ ] 25. UK25 | AppleUSB30XHCIPort | 25 (19000000) | 14900000 | Type 3 // Unmepped
- [ ] 26. UK26 | AppleUSB30XHCIPort | 26 (1a000000) | 14a00000 | Type 3 // Unmepped

## USB2.0-TypeC[8]

- [ ] 2. UK02 | AppleUSB20XHCIPort | 2 (02000000) | 14200000 | Type 3 // Traseira Lado A + B

## USB 3.0 - Type C - With Internal Switch [9]

- [x] 18. AppleUSB30XHCIPort | AppleUSB30XHCIPort | 18 (12000000) | 14200000 |Type3 //Traseira Lado A + B

### Config.plist:

- `ShowPicker:` Habilita ou Desabilita o menu do OpenCore (ESC para abrir menu)
- `HideAuxiliary:` Esconder ferramentas extras do menu (Atalho Barra de espaço)
- `PollAppleHotKeys:` Habilita teclas de atalho macOS (Command+V: Verbose)
