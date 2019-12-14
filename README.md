# Component_list
The electronic components that have been used in the FPGA design 
## DC-DC Converter
- [LMZ31710](http://www.ti.com/lit/ds/symlink/lmz31710.pdf)
    - Input voltage range: [2.95V, 17V]
    - Maximum output current: 10A
    - Efficiency: up to 95%
    - Switching frequency: [200 KHz, 1.2MHz]
    - Operating temperature：[-40℃, 85℃]
    - Package: QFN
- [LTM8027](https://www.analog.com/media/en/technical-documentation/data-sheets/8027fd.pdf)
    - Input voltage range:[4.5V, 60V]
    - Maximum output current: 4A
    - Efficiency: up to 95%
    - Switching frequency: [100 KHz, 500KHz]
    - Operating temperature：[-40℃, 125℃]
    - Package: BGA/LGA
- [LT8645S](https://www.analog.com/media/en/technical-documentation/data-sheets/8645sfa.pdf)
    - Input voltage range:[3.4V, 65V]
    - Maximum output current: 8A
    - Efficiency: up to 95%
    - Switching frequency: [200 KHz, 2MHz]
    - Operating temperature：[-40℃, 125℃]
    - Package: LQFN
## LDO Regulator
- [TPS74401](http://www.ti.com/lit/ds/symlink/tps74401.pdf)
    - Input voltage range: [1.1V, 5.5V]
    - Maximum output current: 3A
    - Adjustable Output: [0.8V, 3.6V]
    - Dropout: 115 mV at 3.0 A (typical)
    - Operating junction temperature：[-40℃, 150℃]
    - Packge: VQFN, RGR, DDPAK

## Voltage Translator

- [TXS0108E](http://www.ti.com/lit/ds/symlink/txs0108e.pdf)
    - 8-bit Bi-directional level shifting
    - Applicable to open-drain and push-pull driver circuits
    - VCCA voltage [1.2V, 3.6V], VCCB voltage [1.65V, 5.5V]
    - Applicable to the open drain 
    - Driven strength is weak
    - PCB trace is as short as possible to avoid the excessive capacitive loading
- *NOTE:* OE referenced to the VCCA
- [TXS0104E](http://www.ti.com/lit/ds/symlink/txs0104e.pdf)
  - 4-bit Bi-directional level shifting
  - VCCA voltage *[1.65V, 3.6V]*, VCCB voltage *[2.3V, 5.5V]*
  - *NOTE:* OE referenced to the VCCA
- [TXS0102E](http://www.ti.com/lit/ds/symlink/txs0102.pdf)
    - 2-bit Bi-directional level shifting
    - VCCA voltage *[1.65V, 3.6V]*, VCCB voltage *[2.3V, 5.5V]*
    - *NOTE:* OE referenced to the VCCA
- [SN74LVC8T245](http://www.ti.com/lit/ds/symlink/sn74lvc8t245.pdf)
    - 8-bit dual-supply level translation & 3-state output
    - Support 5V power supply
    - High driving capability 
- [SN74LV4T125](http://www.ti.com/lit/ds/symlink/sn74lv4t125.pdf)
    - Single Power Supply 
    - CMOS logic level translation
    - High driving capability
-  [SN74AXC4T774](https://www.ti.com/product/SN74AXC4T774)
    - 4-Bit Dual-Supply
    - Applicable to SPI bus

## Voltage Supervisor(PWR-ON Reset)

- [TPS3801xxx](http://www.ti.com/lit/ds/symlink/tps3801.pdf)
    - Power on reset fixed delay
        - TPS3800 = 100 ms
        - TPS3801 = 200 ms 
        - TPS3802 = 400 ms
    - Supply voltage: [2V, 6V]
    - Operating temperature：[-40℃, 85℃]
    - Packge: SOT-23
- 

## ADC
