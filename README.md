# Washing_Machine_Automatic_HDL
This is a Verilog project that implements an automatic control system for a washing machine. The project aims to provide a hardware description language (HDL) implementation of the washing machine control logic, allowing for easy integration into a larger digital system.

The Washing Machine Automatic HDL project offers the following features:

Cycle Selection: The control logic supports different washing cycles, such as normal, gentle, or heavy-duty, allowing users to select the appropriate cycle for their laundry.
Water Level Control: The system adjusts the water level based on the selected cycle, ensuring optimal water usage for different load sizes.
Temperature Control: The control logic manages the heating element to maintain the desired water temperature during the wash cycle.
Timer and Progress Monitoring: The system includes a timer that tracks the progress of the wash cycle and provides status updates to the user.
Implementation Details
The project implements the washing machine control logic using Verilog, a popular HDL used for digital design. The control logic is organized into modules, each responsible for a specific aspect of the washing machine's operation.

The key modules in the project include:

Cycle Selector: This module handles the user interface for cycle selection, allowing the user to choose the desired wash cycle.
Water Level Controller: This module manages the water level control based on the selected cycle and load size.
Temperature Controller: This module controls the heating element to maintain the desired water temperature.
Timer and Progress Monitor: This module tracks the progress of the wash cycle and provides updates to the user interface.
These modules can be instantiated and interconnected to create the complete washing machine control system. Developers can customize the project by adjusting the module configurations or adding additional functionality as per their specific requirements.

Usage
To use the Washing Machine Automatic HDL project in your design, follow these steps:

Clone the repository or download the source code.
Include the required modules in your Verilog design hierarchy.
Instantiate the modules and connect them according to the provided interface definitions.
Simulate or synthesize your design using a Verilog simulator or synthesis tool.
