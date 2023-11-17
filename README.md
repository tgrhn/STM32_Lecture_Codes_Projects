This codes was created during my time in second year of Marmara University Electrical-Electronics Engineering course.
The codes was created for Microprocessor Systems Lecture. 

You can run this codes on STM32 Cube IDE or Keil Studio. In order
Includes:
- Pointer in C.
- Interrupts in microprocessors (C and C++)
- Timers in microprocessors (C and C++)
- GPIO in microprocessors (C and C++)
- Assembly
- ADC/DAC in microprocessors (C and C++)

Also includes two projects:
- Random number generator project in microprocessors (you can look for random_number_generator_full.txt)
- Sensor project (you can look for sensor_pwm_adc_project_stm.txt)

Random Number Generator:
  This project uses stdlib.h library for rand() function. With the help of interrupts, when you press the button, it generates a new number in 7-segment display. If old number and current generated number is same, it will set 1 to LED.

  Sensor project:
    In this project, I used LDR sensor. Light Dependent Resistors are often used as light sensors. They are usually utilized when it is required to detect the presence and absence of light or to measure the light intensity. This project uses ADC to get data from sensor. I designed 9 levels for readings. With the intensity of light, 7-segment display generates which level the intensity of light is. So, it is like a control project.
    
