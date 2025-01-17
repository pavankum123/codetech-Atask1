**NAME**: P.PAVAN KUMAR
**Company**: CODETECH IT SOLUTIONS
**ID**: CT12WDDU
**Domain**: EMBEDDED SYSTEMS
**Duration**: December 9,2024 to March 29,2025
**Mentor**: NEELA SANTHOSH


## Overview of the Project


### Project: PUSH BUTTON COUNTER
![image alt](https://github.com/pavankum123/codetech-task1/blob/71039a2df84e4fc5051157e61e9198ff699bb1fc/Screenshot%202024-12-29%20123306.jpg)

### Objective
The system should accurately count how many times a push button is pressed. Each press increments a counter, which can be displayed to the user.
Mechanical push buttons often generate noise or multiple transitions (bouncing) when pressed or released, which can cause false counting. The system should implement debouncing to ensure that each press is counted only once, avoiding erroneous counts due to button bounce.
The system should display the current count of button presses either on an LCD screen or on a Serial Monitor. This feedback helps the user see how many times the button has been pressed.

### Key Activities
**Button Press Detection**: Set up the button as an input to the microcontroller (e.g., Arduino).
**Button Debouncing**: Implement software debouncing using delays (e.g., delay(50) or using a non-blocking debounce technique with millis()).
**Counting Button Presses**: Set up a variable (e.g., buttonPressCount) to store the count of button presses. 
**Display the Count**: The LCD (e.g., 16x2 I2C LCD) or Serial Monitor is updated each time the button press count changes.
### Technologies Used
**Microcontroller**: The microcontroller is the central unit responsible for handling the logic of detecting button presses, counting, debouncing, and controlling the output display.
**Button (Push Button)**: A physical button is used as the input device for counting. When pressed, it sends a signal (either HIGH or LOW) to the microcontroller, triggering the counting action
**Debouncing Technology**: Mechanical push buttons tend to produce noisy signals when pressed or released, causing multiple transitions (bounces) that may lead to erroneous counting
**LCD (Liquid Crystal Display)**: The I2C protocol is used for communication between the microcontroller and the LCD. It allows for reduced wiring by using just two data pins (SDA and SCL) to communicate with multiple devices.
**Serial Communication**: For debugging or displaying the count on the Serial Monitor instead of an LCD. It allows data to be sent from the microcontroller to the PC (or other devices) via the USB connection.

