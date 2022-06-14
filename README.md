# ADC_POT_EXTI
This project was made using the STM32L073RZTx development board. 
By activating the ADC mode, the LED lighting and extinguishing processes are completed using EXTI according to the values coming from the potentiometer.

PA1 -> ADC_IN1...... Configurations -> NVIC Setting -> Enable 
PE9 -> GPIO_Output
PE10 -> GPIO_Output
PE11 -> GPIO_Output
