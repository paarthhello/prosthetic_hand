EMG-Based Prosthetic Hand Control

Overview

This project is an advanced Arduino-based system that uses multiple electromyography (EMG) sensors to control a prosthetic hand. Each EMG sensor detects muscle activity and translates it into corresponding finger movements using servo motors. The system ensures smooth and accurate control by implementing noise filtering and customized activation thresholds.

Features

Multi-Sensor Support: Supports multiple EMG sensors to control different fingers independently.

Noise Filtering: Uses an averaging method to stabilize EMG readings.

Customizable Thresholds: Each sensor has its own activation threshold for precise control.

Real-Time Monitoring: Serial output for debugging and fine-tuning sensor sensitivity.

Optimized Performance: Efficient loop execution with minimal delays to enhance responsiveness.

Hardware Requirements

Arduino board (Uno, Mega, or compatible)

EMG sensors (at least 3 for independent finger control)

Servo motors (1 per finger)

Jumper wires and breadboard

Power supply (external recommended for servo motors)

Installation & Setup

Connect the EMG sensors to the Arduino's analog input pins (A0, A1, A2, etc.).

Connect servo motors to PWM pins (9, 10, 11, etc.).

Adjust the threshold values in the code based on sensor calibration.

Upload the provided Arduino sketch to the board.

Open the Serial Monitor to observe EMG signal values and adjust accordingly.

Usage

When muscle activity exceeds the threshold, the corresponding finger closes.

When muscle activity drops below the threshold, the finger opens.

The system continuously monitors and adapts to EMG signals for responsive movement.

Future Enhancements

Implement machine learning for adaptive threshold adjustments.

Add Bluetooth/WiFi connectivity for remote control and data logging.

Enhance filtering techniques for improved precision.

License

This project is open-source and available for modification and improvement. Feel free to contribute and enhance the functionality!
