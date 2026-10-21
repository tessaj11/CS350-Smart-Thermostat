# CS350-Smart-Thermostat
Raspberry Pi smart thermostat project for CS 350 using Python, temperature sensing, LED indicators, LCD display, and UART communication

For CS 350, I worked with a Raspberry Pi to learn how software interacts with hardware. I selected two projects for my portfolio: the Morse Code LED project from Milestone Three and the Thermostat Final Project.

The Morse Code project involved using Python to control red and blue LEDs to display Morse code messages. The program used a state machine to control the timing of each light and a button to switch between SOS and OK. It also included a 16x2 LCD display to show the message being transmitted.

For the final project, I developed Python code for a thermostat system that could switch between heating, cooling, and off states. The program was designed to read temperature data from a sensor, adjust a temperature setpoint using buttons, control LED indicators, display information on an LCD, and send updates through serial communication. I completed the code, but hardware issues prevented me from fully testing the final system.

## What did you do particularly well?

I think I did well with troubleshooting and learning how the different hardware components worked together. The Morse Code project helped me become more comfortable working with GPIO pins, LEDs, buttons, and state machines. I also got better at navigating the Raspberry Pi terminal and identifying problems in my code or wiring.

## Where could you improve?

I could improve how I plan and test my hardware connections before putting everything together. During the final project, I ran into hardware issues that made it difficult to test the program. I learned that having the code written is only one part of completing a hardware project. I want to get better at testing individual components first so I can identify problems earlier.

## What tools and resources are you adding to your support network?

I gained experience using Python, Raspberry Pi, GPIO libraries, Linux commands, and draw.io for state machine diagrams. I also became more familiar with using course resources and documentation to troubleshoot errors. These are tools I can continue using as I work on other programming projects.

## What skills from this project will transfer to other projects or coursework?

Troubleshooting and debugging are probably the biggest skills I will take from this course. I also learned how useful state machines are for organizing a program that needs to respond to different inputs. Understanding how software communicates with hardware can help me with future programming projects, especially those involving embedded systems or connected devices.

## How did you make this project maintainable, readable, and adaptable?

I used functions and state machines to organize the programs into different sections based on their responsibilities. For example, the Morse Code program separates the LED behavior, message selection, and display updates. The thermostat code also separates temperature readings, LED controls, button inputs, and display updates. This makes it easier to understand what each part of the program does and where changes would need to be made. It also allows the programs to be adjusted later without having to rewrite everything.

## Portfolio Artifacts

- **Milestone Three – Morse Code LED Project:** Python application using LEDs, a button, an LCD display, and a state machine to transmit Morse code messages.
- **Final Project – Thermostat:** Python application designed to control thermostat states, read temperature data, display information, and communicate through a serial connection. Hardware testing was not completed due to equipment issues.
