# LGH1ScooterPackPower
A way to wake up the e-scooter pack sold by Jehu Garcia https://www.youtube.com/watch?v=E87EcLeqIX0


Works with STM32F103 board


Make shure you use the STM32 core 1.90. A tutorial how to use the new core is here: https://www.electronicshub.org/getting-started-with-stm32f103c8t6-blue-pill/

PA2 -  This is the LED for confirming On/Off

PB5 - ON/OFF switch (same as boot 0, so it must be disconnected before powering up the board)

CAN_RX mapped to PA11, CAN_TX mapped to PA12
