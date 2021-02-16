# STM32f746G_Discovery_UART
>This is a test which is using STM32f746G_Discovery  to send data to computer

# Goal
### Create 3 modes to control the led、lcd、UART to show respectively act
- mode 1:
  - LED glows one time per 100ms
  - COM port sends string "MODE 1, LED FLASH = 5Hz"
  - LCD　shows string "MODE 1, LED FLASH = 5Hz" 
- mode 2:
  - LED glows one time per 500ms
  - COM port sends string "MODE 2, LED FLASH = 1Hz"
  - LCD　shows string "MODE 2, LED FLASH = 1Hz" 
- mode 3:
  - LED OFF
  - COM port sends string "MODE 3, LED FLASH = 0Hz"
  - LCD　shows string "MODE 3, LED FLASH = 0Hz" 
# Bottom and led
![](user%20bottom%20led.jpg)

# Using function
1. GPIO_EXIT(PI11)
2. Timer
3. LED(PI1)
4. LCD
5. UART TX (PA9)
6. UART RX (PB7)

# reference
1. https://applefreak111.wordpress.com/2013/05/08/howto-stm32-%E4%B8%AD%E6%96%B7-%E5%A4%96%E9%83%A8%E4%B8%AD%E6%96%B7-%E6%95%99%E5%AD%B8/
2. https://www.twblogs.net/a/5d52ad86bd9eee541c31686c (timer)