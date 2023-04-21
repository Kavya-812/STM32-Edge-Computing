# Vibration-based Predictive Maintenance System

This project is a vibration-based predictive maintenance system that uses an MPU sensor and STM401RE microcontroller to detect anomalies in vibration data. The system collects vibration data using NanoEdge Studio, and uses anomaly detection to classify the data. The system can be used for predictive maintenance in industrial settings, where anomalies in vibration data can indicate potential failures in machinery.

## Requirements

To run this project, you will need the following:

- STM401RE microcontroller
- MPU sensor
- NanoEdge Studio
- IDE or text editor for editing and uploading the code to the microcontroller
- USB cable for connecting the microcontroller to your computer

## Installation

1. Clone or download this repository to your local machine.
2. Open the project folder in your STM CUBE IDE 
3. Connect the MPU sensor to your microcontroller as per the hardware specifications.
4. Open the FinalMPU.c file in your IDE or text editor and upload it to the microcontroller.
5. In NanoEdge Studio, create a new project and select "Vibration" as the input type.
6. Define two classes for your project: "Normal" and "Abnormal".
7. Collect data for each class using the MPU sensor connected to the microcontroller.
8. Upload the data to NanoEdge Studio and train the model.
9. Once the model is trained and the accuracy is satisfactory, download and import the model files to STM32Cube IDE.
10. Create a new project in STM32Cube IDE and upload the 'FinalMPU.c' and 'nanoedge.h' files.
11. Compile the code and upload it to the microcontroller.
12. Monitor the output in the serial plot of the Arduino IDE.

## Usage

1. Connect the MPU sensor to the microcontroller and power on the system.
2. The system will collect vibration data using the MPU sensor.
3. The data will be processed by the microcontroller and the classification result will be displayed in the serial plot of the Arduino IDE.
4. Anomalies in the vibration data will be classified as "Abnormal", while normal vibration data will be classified as "Normal".

## Contributing

If you would like to contribute to this project, please fork the repository and create a pull request with your changes. We welcome contributions from the community!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

