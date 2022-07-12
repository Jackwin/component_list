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
- [TLV62130](https://www.ti.com/lit/ds/symlink/tlv62130.pdf?HQS=dis-dk-null-digikeymode-dsf-pf-null-wwe&ts=1657604874340&ref_url=https%253A%252F%252Fwww.ti.com%252Fgeneral%252Fdocs%252Fsuppproductinfo.tsp%253FdistId%253D10%2526gotoUrl%253Dhttps%253A%252F%252Fwww.ti.com%252Flit%252Fgpn%252Ftlv62130)
    - Input voltage range:[3V, 17V]
    - Maximum output current: 3A
    - Switching frequency: [1250 KHz, 2500KHz]
    - Package: QFN
## LDO Regulator
- [TPS74401](http://www.ti.com/lit/ds/symlink/tps74401.pdf)
    - Input voltage range: [1.1V, 5.5V]
    - Maximum output current: 3A
    - Adjustable Output: [0.8V, 3.6V]
    - Dropout: 115 mV at 3.0 A (typical)
    - Operating junction temperature：[-40℃, 150℃]
    - Packge: VQFN, RGR, DDPAK
- [MAX8902BATA+T](https://datasheets.maximintegrated.com/en/ds/MAX8902-MAX8902B.pdf)
  - Low noise 500mA LDO
  - Input voltage range:[1.7, 5.5]
  - Adjustable Output: 1.5V, 1.8V, 2.0V, 2.5V, 3.0V, 3.1V, 3.3V, 4.6V, or 4.7V
  - 2mm x 2mm x 0.8mm TDFN Package

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
    

## ADC

- [AD9434](https://www.analog.com/media/en/technical-documentation/data-sheets/AD9434.pdf)
  - 12-Bit 370/500 MSPS 1.8V AD converter
  - Support SDR/DDR output format
  - 1.8V analog and digital supply voltage

- [AD9826](https://www.analog.com/media/en/technical-documentation/data-sheets/AD9826.pdf)
  - 16-Bit image signal processor
  - 3-channel 16-Bit operation up to 15MSPS
  -  1-Channel 16-Bit Operation up to 12.5 MSPS 
  - Support RGB channel sampling for the image processing
  - 3V/5V IO compatibility

## Clock Generator

- [AD9517-3](https://www.analog.com/media/en/technical-documentation/data-sheets/AD9517-3.pdf)
  - 12-channel output clocks
  - Integrated 2.0 GHz VCO or external VCO/VCXO to 2.4 GHz
  - 4 LVPECL outputs @ 1.6 GHz LVPECL outputs with jitter @ 225 fs rms
  - 4  LVDS clock outputs @ 800 MHz with jitter @ 275 fs rms
  - 4 LDVS outputs can be configured as 8 CMOS outputs

## DAC

## DDR

## Oscillator

## Peripheral 