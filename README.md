# CS-350-Emerging-Systems-Architecture

This repo was the major assignment for my CS 350: Emerging Systems Architecture & Design at Southern New Hampshire University.

<img width="1616" alt="Screen Shot 2025-06-29 at 5 02 06 PM" src="https://github.com/user-attachments/assets/b1d5bd3f-ceaf-4294-8aef-f0fa42f3f5f6" />

1. Summarize the project and what problem it was solving.

In this project, I built a prototype of a smart embedded thermostat system using a Raspberry Pi. The thermostat monitors temperature and humidity via an AHT2 sensor and allows user interaction through GPIO buttons and LCD display output. It simulates HVAC control and UART-based server communication, and allows a user to interact with the HVAC system using physical controls on an embedded system.

2. What did you do particularly well?

I enjoyeed integrating multiple hardware components—such as the temperature sensor, buttons, status LEDs, and the LCD—into a cohesive and functional system. I also enjoyed creating clean, modular Python code that handled real-time input and output reliably.

3. What tools and/or resources are you adding to your support network?

I’ve added resources like the Raspberry Pi GPIO Python library documentation, UART communication examples, and datasheets for embedded components to my toolbox. Additionally, hands-on experience using breadboards, circuit diagrams, and debugging hardware and multimeters has expanded my embedded systems skills.

4. What skills from this project will be particularly transferable to other projects and/or course work?

Skills in hardware-software integration, GPIO interrupt management, and I2C/UART communication are highly transferable to future embedded systems or IoT projects.

5. How did you make this project maintainable, readable, and adaptable?

I structured my code using functions for each subsystem (e.g., temperature read, button handling, UART messaging), making it easier to debug and extend. Clear variable names, inline comments, and a simple state machine model ensured that the system logic was transparent and easy to adapt for future enhancements.
