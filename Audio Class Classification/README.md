# Audio Classification System using STM32-401RE Microcontroller

This project is an audio classification system that uses an STM32-401RE microcontroller and NanoEdge software to classify three different types of audio: baby cry, ambulance siren, and random noises.

## Requirements

To run this project, you will need the following:

- STM32-401RE microcontroller
- NanoEdge software
- Audio data for each of the three classes (baby cry, ambulance siren, and random noises)
- STM32Cube IDE for creating the code for the microcontroller
- USB cable for connecting the microcontroller to your computer
- Audio Sensor 

## Installation

1. Clone or download this repository to your local machine.
2. Open the project folder in STM32Cube IDE.
3. Connect the STM32-401RE microcontroller to your computer using a USB cable.
4. Open the `main.c` file in STM32Cube IDE and upload it to the microcontroller.

## Usage

1. Launch NanoEdge software and create a new project.
2. Select "N-classifier" for the classification project and choose the "Audio" input type with an appropriate sampling rate for your audio data.
3. Define three classes for your project: "Baby Cry", "Ambulance Siren", and "Random Noises".
4. Collect audio data for each class using NanoEdge.
5. Use NanoEdge to visualize the collected data as scatter plots and perform data testing.
6. Analyze the accuracy, confusion matrix, and model being used in the classification process.
7. Open STM32Cube IDE and create a new project, modifying the ioc file as required.
8. Add the exported files to your project and create a new folder with "Inc" and "Lib" as subfolders.
9. Add "knowledge.h" and "NanoEdgeAI.h" to "Inc" and "libneai.a" to "Lib".
10. Compile and upload the code to the microcontroller.
11. Connect the microcontroller to your computer and open a serial monitor to view the classification system's output.
12. Play the audio samples and observe the results in the serial monitor, which will display the classification results are shown in serial monitor.




## Contributing

We welcome contributions from the community! If you would like to contribute to this project, please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

