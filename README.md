# Emerging Systems Architectures and Technologies Portfolio

## Project Artifacts

This repository contains two project artifacts that reflect my work in emerging systems architectures and technologies:

- **Thermostat.py**: A prototype for a smart thermostat, designed to interact with hardware components and simulate embedded systems behavior.
- **Milestone3.py**: A Python program demonstrating a state machine that uses Red and Blue LEDs to display Morse code messages ("SOS" and "OK"). The message toggles based on button presses.

---

## Reflection

### Summarize the project and what problem it was solving
**Thermostat.py** simulated the basic functionality of a smart thermostat, focusing on interacting with hardware inputs and outputs while maintaining system control and user feedback.  
**Milestone3.py** demonstrated how to use a state machine to control LEDs and display Morse code messages based on user input (button press). It solved the problem of managing hardware outputs (LEDs) and inputs (buttons) in a responsive and reliable way within a constrained embedded environment.

### What did you do particularly well?
I implemented clean and modular code, especially in managing the state transitions for Milestone 3. I also successfully created readable logic that would be easy to adapt for more complex messages or additional hardware components.

### Where could you improve?
One area for improvement would be optimizing the timing functions for even more precise Morse code signaling. Additionally, I could improve the abstraction level to better separate the hardware control from the state machine logic, making future adaptations even easier.

### What tools and/or resources are you adding to your support network?
I incorporated Python libraries for hardware simulation, additional documentation practices like README and code comments, and deeper research into embedded systems design patterns such as event-driven programming and finite state machines.

### What skills from this project will be particularly transferable to other projects and/or course work?
- State machine design and implementation
- Hardware and software integration principles
- Modular programming and abstraction
- Writing clear, maintainable, and scalable code
- Debugging timing-sensitive hardware control systems

### How did you make this project maintainable, readable, and adaptable?
I followed consistent naming conventions, wrote meaningful comments, and separated logical components (state transitions, hardware interactions, message handling) into manageable sections. This makes it easy to modify the system to handle new states, new messages, or even different hardware setups.

---

## Repository Structure
