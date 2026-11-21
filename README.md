# STM32F103 Bluetooth RC Robot

2WD differential drive robot controlled over Bluetooth (`HC-05`) using an STM32F103C8T6 (Blue Pill) and a `DRV8833` motor driver.

## Hardware Used
- **MCU:** STM32F103C8T6 (Blue Pill)
- **Motor Driver:** DRV8833
- **Bluetooth:** HC-05 (`USART1` on `PA9` TX, `PA10` RX at 9600 baud)
- **PWM Timer:** `TIM2` on `PA0`–`PA3`
- **Power:** 18650 Li-ion cell with proper voltage regulation / isolated logic rail

## Serial Commands
- `F` : Forward
- `B` : Backward
- `L` : Left
- `R` : Right
- `S` : Stop

// i wanted to build my own car from childhood i  have finally built as to be come embedded iot firmaware and edge Ai integration engineer . I built this RC Robot and used multiple modules and connected and coded stm 32 board properly to get the result . I have some issues after assembling everything when it did't worked but after fixiing some inter setting for my stm32 board it workign fine .
to see read its detailed description of working and parts see my linkding www.linkedin.com/in/yashbisen
