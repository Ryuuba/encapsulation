# Llenado del encabezado TCP

## Datos del encabezado
```
0000  ca 23 00 50 eb 06 42 73  2c d8 8d 52 50 18 02 00   ·#·P··Bs ,··RP···
0010  19 15 00 00
```           

## Formato del encabezado

![TCP format](https://upload.wikimedia.org/wikipedia/commons/c/c8/Ntwk_tcp_header123.jpg "Formato de la cabecera TCP")

## Campos del encabezado

```
Source port: 0xca23
Destination port: 0x0050
Sequence number: 0xeb064273
ACK number: 0x2cd88d52
Data offset: 0101
Reserved: 000000
URG: 0
ACK: 1
PSH: 1
RST: 0
SYN: 0
FIN: 0
Window: 0x0200
Checksum: 0x1915
Urgent pointer: 0x0000
```