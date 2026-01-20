# 5x5 Tileable Minibadge Display

<img  height="600" alt="image" src="https://github.com/user-attachments/assets/3d1f42c5-d042-45a9-92a0-13e7450d317c" />

## Details

A magnetically tileable 5x5 Minibadge display designed around USB-C PD input. This board accepts 5V - 28V and carries that voltage as the backplane for connected boards. Power input is regulated to 5V and 3.3V per board. It features a wide range of protections for shorts, over/under voltage, hotplugging, and ESD. 

### Features
* Wide voltage range input for various PD VBUS voltages (5V - 28V)
* Modular tileability using magnetic pogo pins
* Backplane scaleable to many hundreds of minibadges across many pannels

### Specifications
**Parameter**|**Value**
:-----:|:-----:
Input voltage|5V – 28V (USB-C PD)
Max input current|3.2A (Fuse-limited)
Minibadge rails|3.3V, 5V, CLK
Max output current|3.3V@3A, 5V@3A
Typical load|~13 W per board (3.3V@150mA per badge) 
Sockets|25 minibadges (5×5)
Indication|5V, 3V, CLK
Protection methods|TVS on connectors, ESD for CLK, Reverse polarity, Short protection
