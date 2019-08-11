# Component_list
The electronic components that I have used in the FPGA design 

## Voltage Translator
- [TXS0108E](http://www.ti.com/lit/ds/symlink/txs0108e.pdf)
    - 8-bit Bi-directional level shifting
    - Applicable to open-drain and push-pull driver circuits
    - VCCA voltage [1.2V, 3.6V], VCCB voltage [1.65V, 5.5V]
- *NOTE:* OE referenced to the VCCA
- [TXS0104E](http://www.ti.com/lit/ds/symlink/txs0104e.pdf)
  - 4-bit Bi-directional level shifting
  - VCCA voltage *[1.65V, 3.6V]*, VCCB voltage*[2.3V, 5.5V]*
  - *NOTE:* OE referenced to the VCCA
- [TXS0102E](http://www.ti.com/lit/ds/symlink/txs0102.pdf)
    - 2-bit Bi-directional level shifting
    - VCCA voltage *[1.65V, 3.6V]*, VCCB voltage*[2.3V, 5.5V]*
    - *NOTE:* OE referenced to the VCCA

