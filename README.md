## <meta name="google-site-verification" content="kvGR7XNw5qGt7n3RQNOOJbI50O_4_Ufc8E3ax_qpPJY" />

# AI Surveillance Robot with ESP32-CAM and Arduino
hello didi kaise ho aap

This project is an AI-powered surveillance robot using ESP32-CAM and Arduino. The robot detects motion, starts recording video, and avoids obstacles while navigating autonomously. The system features real-time video streaming, motion detection, and a buzzer alert. It's a comprehensive surveillance solution for monitoring environments.

## Features

- **Motion Detection**: Uses PIR sensor to detect motion.
- **Video Streaming**: The ESP32-CAM captures and streams live video.
- **Obstacle Avoidance**: The robot moves autonomously, avoiding obstacles using the ultrasonic sensor.
- **Alert System**: A buzzer sounds and the LCD shows "Motion Detected" when motion is detected.
- **Live Recording**: The system starts recording video when motion is detected.
  
## Getting Started
## Project Image URL:
# AI Surveillance Robot with ESP32-CAM and Arduino

This project is an AI-powered surveillance robot using ESP32-CAM and Arduino. The robot detects motion, starts recording video, and avoids obstacles while navigating autonomously. The system features real-time video streaming, motion detection, and a buzzer alert. It's a comprehensive surveillance solution for monitoring environments.

## Features

- **Motion Detection**: Uses PIR sensor to detect motion.
- **Video Streaming**: The ESP32-CAM captures and streams live video.
- **Obstacle Avoidance**: The robot moves autonomously, avoiding obstacles using the ultrasonic sensor.
- **Alert System**: A buzzer sounds and the LCD shows "Motion Detected" when motion is detected.
- **Live Recording**: The system starts recording video when motion is detected.
  
## Getting Started
## Project image URL:
https://www.tinkercad.com/things/76acSpBByAz-arthav-project


### Prerequisites

Before you begin, ensure you have the following:

- **Hardware**:
  - Arduino Uno or any compatible board.
  - ESP32-CAM module.
  - PIR Motion Sensor.
  - Ultrasonic Sensor (HC-SR04).
  - BO gear motors and motor driver.
  - LCD display (16x2).
  - Buzzer.

- **Software**:
  - **Arduino IDE**: Install Arduino IDE to write and upload the code.
  - **ESP32 Board Support**: Install ESP32 board support in Arduino IDE.
  - **Libraries**:
    - ESP32CAM library.
    - Servo library.
    - LCD library (for 16x2 LCD).

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/[YourUsername]/AI-Surveillance-Robot.git
    ```

2. **Upload the code**:
    - Program the ESP32-CAM using an FTDI programmer.
    - Upload the Arduino code to the Arduino Uno (or compatible board) via the Arduino IDE.

3. **Hardware Connections**:
    - **ESP32-CAM**:
      - 5V to 5V of the FTDI programmer.
      - GND to GND of the FTDI programmer.
      - TX to RX (of FTDI programmer).
      - RX to TX (of FTDI programmer).
      - GPIO0 connected to GND for programming mode.
    - **PIR Sensor**: 
      - VCC to 5V (Arduino).
      - GND to GND (Arduino).
      - OUT to a digital input pin (e.g., D2).
    - **Ultrasonic Sensor**: 
      - VCC to 5V.
      - GND to GND.
      - TRIG to a digital output pin (e.g., D3).
      - ECHO to a digital input pin (e.g., D4).
    - **LCD Display**:
      - VCC to 5V.
      - GND to GND.
      - SDA to A4 (Arduino).
      - SCL to A5 (Arduino).
    - **Motors**:
      - Use motor driver to connect motors to the Arduino.

### Usage

Once the system is powered up:

1. The robot will start moving autonomously.
2. When the PIR sensor detects motion, the buzzer will activate, and the LCD will display "Motion Detected".
3. Simultaneously, the ESP32-CAM will begin streaming live video, and it will start recording.
4. The ultrasonic sensor will ensure the robot avoids obstacles while moving.

### How to Run

1. Connect the robot to a power source.
2. The system will automatically begin moving and monitoring.
3. It will alert you whenever motion is detected and start recording.

## Contributing

Feel free to contribute by forking the project, making improvements, and submitting a pull request.

Steps for contribution:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make changes and commit (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspiration from various Arduino and ESP32 projects.
- Thanks to the open-source community for libraries and tools.
- Special thanks to contributors and collaborators who helped improve the project.



### Prerequisites

Before you begin, ensure you have the following:

- **Hardware**:
  - Arduino Uno or any compatible board.
  - ESP32-CAM module.
  - PIR Motion Sensor.
  - Ultrasonic Sensor (HC-SR04).
  - BO gear motors and motor driver.
  - LCD display (16x2).
  - Buzzer.

- **Software**:
  - **Arduino IDE**: Install Arduino IDE to write and upload the code.
  - **ESP32 Board Support**: Install ESP32 board support in Arduino IDE.
  - **Libraries**:
    - ESP32CAM library.
    - Servo library.
    - LCD library (for 16x2 LCD).

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/[YourUsername]/AI-Surveillance-Robot.git
    ```

2. **Upload the code**:
    - Program the ESP32-CAM using an FTDI programmer.
    - Upload the Arduino code to the Arduino Uno (or compatible board) via the Arduino IDE.

3. **Hardware Connections**:
    - **ESP32-CAM**:
      - 5V to 5V of the FTDI programmer.
      - GND to GND of the FTDI programmer.
      - TX to RX (of FTDI programmer).
      - RX to TX (of FTDI programmer).
      - GPIO0 connected to GND for programming mode.
    - **PIR Sensor**: 
      - VCC to 5V (Arduino).
      - GND to GND (Arduino).
      - OUT to a digital input pin (e.g., D2).
    - **Ultrasonic Sensor**: 
      - VCC to 5V.
      - GND to GND.
      - TRIG to a digital output pin (e.g., D3).
      - ECHO to a digital input pin (e.g., D4).
    - **LCD Display**:
      - VCC to 5V.
      - GND to GND.
      - SDA to A4 (Arduino).
      - SCL to A5 (Arduino).
    - **Motors**:
      - Use motor driver to connect motors to the Arduino.

### Usage

Once the system is powered up:

1. The robot will start moving autonomously.
2. When the PIR sensor detects motion, the buzzer will activate, and the LCD will display "Motion Detected".
3. Simultaneously, the ESP32-CAM will begin streaming live video, and it will start recording.
4. The ultrasonic sensor will ensure the robot avoids obstacles while moving.

### How to Run

1. Connect the robot to a power source.
2. The system will automatically begin moving and monitoring.
3. It will alert you whenever motion is detected and start recording.

## Contributing

Feel free to contribute by forking the project, making improvements, and submitting a pull request.

Steps for contribution:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make changes and commit (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspiration from various Arduino and ESP32 projects.
- Thanks to the open-source community for libraries and tools.
- Special thanks to contributors and collaborators who helped improve the project.


