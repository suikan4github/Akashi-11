# Akashi-11
Prototype of the EL-210 mod 

## Description

This board is prototype of the EL-210 mode board. Akashi-11 si designed to mount on the 
[Nucleo G0B1RE](https://www.st.com/ja/evaluation-tools/nucleo-g0b1re.html) board and 
to be connected with the  [Akashi-10 board](https://github.com/suikan4github/Akashi-10) in EL-210. 

The battery power is provided from the EL-210 through a ribbon cable. This power is 
boosted on the board to be a 3.3V. And provided to Nucleo through the pin 12 and 16 of 
the CN7. To avoid an accident, the bridge SB1 on the Nucleo G0B1RE must be cut. 

Signal assignment of Nucleo is as following : 

| Signal | GPIO Pin |
|-|-|
| KEY1 | PA10 |
| KEY2 | PB3 |
| KEY3 | PB5 |
| KD0 | PA5 |
| KD1 | PA6 |
| KD2 | PC1 |
| KD3 | PB0 |
| KD4 | PC7 |
| KD5 | PB2 |
| KD6 | PB6 |
| KD7 | PB14 |
| KD8 | PB4 |
| SPI1_MOSI | PA12 |
| SPI1_SCK | PD8 |
| LOAD | PC10 |
| BLANK | PC12 |
| TIM1_CH1 | PA8 |
| TIM1_CH1N | PA7 |
| TIM2_CH1 | PA9 |
