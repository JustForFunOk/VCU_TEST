# VCU_TEST

This project is used to test function on evaluation board. All the code will be migrated to new hardware in my SmartCar.

## Environment

HW: `STM32F103ZET6`

IDE: `STM32CubeIDE`

LIB: `HAL`+`LL`

## Pinout Configuration

|Pin name|Pin Function| Used to| Used to |
|:--:|:--:|:--:|:--:|
|PB0|TIM3_CH3|PWM output|contorl motor|
|PB1|TIM3_CH4|PWM output|control servo|
|PA2|TIM2_CH3|PWM Input Capture|measure motor rotation speed </br>(not recommond) |
|PE9</br>PE11|TIM1_CH1</br>TIM1_CH2|Encoder|measure motor rotation </br> speed(recommond) </br>direction</br>acceleration |
|PB6</br>PB7|I2C1_SCL</br>I2C1_SDA|IIC Communicate|IMU data|

