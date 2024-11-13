# Speed-Control-of-Motor-using-Buck-Boost-converter

## Overview
This project demonstrates the speed control of a DC motor using a buck-boost converter. The buck-boost converter is used to regulate the voltage supplied to the motor, enabling precise control over its speed. This project can serve as a practical demonstration of power electronics concepts, including voltage regulation, control algorithms, and motor speed control.

## Features
- **Voltage Control with Buck-Boost Converter**: Adjusts the voltage supplied to the motor to control speed.
- **Closed-Loop Feedback**: Uses feedback from the motor to maintain a desired speed, even with load variations.
- **PWM Control**: Implements Pulse Width Modulation (PWM) for effective control of the buck-boost converter.
- **Simulation Support**: MATLAB/Simulink or any other compatible tool can be used to simulate the setup.

## Project Structure
- **`/src`**: Contains source code files.
- **`/docs`**: Documentation files, including theory and design calculations.
- **`/simulations`**: Simulink or other simulation files for testing the converter.
- **`README.md`**: Project overview and setup guide (this file).

## Requirements
- **Hardware**:
  - DC Motor
  - Buck-Boost Converter
  - Microcontroller (e.g., Arduino, STM32) or any other controller
  - Power Supply and basic electronic components
- **Software**:
  - MATLAB/Simulink (for simulation)
  - Microcontroller programming environment (e.g., Arduino IDE)

## Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. **Open Simulation Files** (if using MATLAB/Simulink) and run the initial tests to understand converter behavior.
3. **Upload Code to Microcontroller** (if applicable) and set up the hardware as specified in the wiring diagrams.

## Usage
1. Set the desired speed for the motor by adjusting the target voltage in the control code or simulation parameters.
2. Run the simulation or power on the hardware circuit.
3. Observe the motor speed and voltage feedback in the data logger or oscilloscope.
4. Modify PWM duty cycle to change the motor speed and observe the response.

## Theory
The buck-boost converter adjusts the voltage supplied to the motor by stepping it up or down, which directly influences motor speed. A closed-loop feedback mechanism is employed to regulate the motor's speed by adjusting the duty cycle of the PWM signal.

### Control Strategy
- **PWM Control**: Pulse Width Modulation is used to regulate the voltage by varying the duty cycle.
- **Feedback Loop**: A sensor (such as a tachometer) is used to measure motor speed, feeding data back to adjust the PWM duty cycle.

## Simulation
The provided simulation files demonstrate the operation of the buck-boost converter for motor control, including both open-loop and closed-loop configurations. This setup is ideal for verifying the design parameters before implementation on actual hardware.

## Results
Results, including speed response curves and system stability analysis, can be found in the `/results` folder. These results demonstrate the effectiveness of the buck-boost converter in regulating motor speed under varying load conditions.
![BUCK_BOOST_SPEED_CONTROL_page-0002](https://github.com/user-attachments/assets/dc958896-3803-4866-82f3-3e8f260ae69a)


## Contributing
Feel free to contribute by:
- Forking the repository
- Creating an issue for feature requests or bug reports
- Submitting a pull request

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments
This project is inspired by concepts from power electronics and control systems courses. Special thanks to instructors and online resources that contributed to the theoretical background of this project.

--- 

This template covers all essential aspects, providing clear instructions, setup guidance, and a project overview. Adjust details like file paths, hardware specifics, and testing details as per your project’s design.
