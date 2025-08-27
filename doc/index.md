---
title: Bus
nav_order: 2
parent: Hardware
---

# Bus PCB

<table>
  <tr><th>Top</th><th>Bottom</th></tr>
  <tr>
    <td><img src="main-3D_top.png?dummy={{ site.data['hash'] }}" alt="top" /></td>
    <td><img src="main-3D_bottom.png?dummy={{ site.data['hash'] }}" alt="bottom" /></td>
  </tr>
</table>

Die `Bus` Platine verteilt die benötigten Versorgungsspannungen (+5V und +12V) zu allen Modulen. Weiters ist ein USB-Hub auf der Rückseite der Platine vorhanden um dem CM4-Modul Zugriff zu den Devices zu geben.
Die Platine welche die benötigten Versorgungsspannungen zur Verfügung stellt hat auch noch eine I<sup>2</sup>C Bus Verbindung zum CM4-Modul um die Spannungen und Ströme auslesen zu können.

| Spannung | benötigter Strom |
| -------- | ---------------- |
|      +5V |            100mA |
|     +12V |                - |

## Daten

- [Schaltplan](main-schematic.pdf)
- [BOM](main-bom.html)
- [iBOM](main-ibom.html)
- [JLCPCB fabrication & stencil](JLCPCB/main-_JLCPCB_compress.zip)
- [JLCPCB Bom](JLCPCB/main_bom_jlc.csv)
- [JLCPCB Pick&Place](JLCPCB/main_cpl_jlc.csv)
