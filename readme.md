The FreeRTOS_pico2w folder contains a barebones FreeRTOS project, which can run on a RPi Pico 2W. It starts a single task, which printf's to the UART.

A walkthrough of how to recreate this project is in [freertos_pico2w.md](https://github.com/michaelloftdk/rpipico2w_freertos/blob/main/docs/freertos_pico2w.md)

Source files used for the project was downloaded on 20250903 and 20250904 from:
- Raspberry Pi FreeRTOS examples https://github.com/raspberrypi/FreeRTOS-Kernel/tree/main/examples
- Raspberry Pi FreeRTOS pico examples https://github.com/raspberrypi/pico-examples/tree/master/freertos
- RP2350 FreeRTOS port https://github.com/raspberrypi/FreeRTOS-Kernel/tree/main/portable/ThirdParty/GCC/RP2350_ARM_NTZ
