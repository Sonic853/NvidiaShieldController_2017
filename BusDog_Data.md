### PID & VID
1. USB:
    PID = 0x7214 , VID = 0x0955

2. Bluetooth:
    PID = 0x7214 , VID = 0x0955

### BusDog Hex
Pos  |Value    |Note
-----|---------|----
0    |01       |ReportID?
1    |00-FF    |Button count
2    |80<br>00<br>01<br>02<br>03<br>04<br>05<br>06<br>07 |No input<br>D-Pad:UP<br>D-Pad:UP+Right<br>D-Pad:Right<br>D-Pad:Right+Down<br>D-Pad:Down<br>D-Pad:Down+Left<br>D-Pad:Left<br>D-Pad:Left+UP
3    |00<br>01<br>02<br>04<br>08<br>10<br>20<br>40<br>80 |No input<br>A<br>B<br>X<br>Y<br>L1<br>R1<br>Left Stick Btn<br>Right Stick Btn
4    |00<br>01 |No input<br>Bottom Middle Btn
5-6  |0000-FFFF|Left Trigger
7-8  |0000-FFFF|Right Trigger
9-12 |00800080<br>XXXX0000<br>XXXXFFFF<br>0000XXXX<br>FFFFXXXX |Normal<br>Left Stick Y UP<br>Left Stick Y Down<br>Left Stick X Left<br>Left Stick X Right
13-16|00800080<br>XXXX0000<br>XXXXFFFF<br>0000XXXX<br>FFFFXXXX |Normal<br>Right Stick Y UP<br>Right Stick Y Down<br>Right Stick X Left<br>Right Stick X Right
17   |00<br>01<br>02<br>04 |No input<br>Bottom Right Btn<br>Bottom Left Btn<br>Nvidia Btn
18   |00<br>01<br>02 |No input<br>Touchpad Slide UP<br>Touchpad Slide Down
### Shock
None
