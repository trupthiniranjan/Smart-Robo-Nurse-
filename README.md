# Smart-Robo-Nurse-
An IoT-based Smart Robo Nurse system designed for intelligent home-based patient monitoring, health tracking, and automated medication assistance.
# 🤖 Smart Robo Nurse for Post-Surgery Patients

An IoT-based healthcare monitoring and assistance system designed
to support patients recovering from surgery through vital-sign
monitoring, remote health data access, medication reminders,
and assisted medicine dispensing.

## 📌 Project Overview

Smart Robo Nurse is an intelligent healthcare assistance system
that integrates the Internet of Things (IoT), embedded systems,
cloud computing, robotics, and AI-assisted medicine information.

The system consists of an ESP32-based bedside monitoring unit and
a Raspberry Pi-based robotic station. It collects selected
physiological measurements and sends monitoring data to Google
Firebase for access through doctor and guardian dashboards.

The system also incorporates medication reminders, a linear
actuator-based medicine dispensing mechanism, and an AI-assisted
chatbot for medicine-related information.

## ✨ Key Features

- ❤️ **Vital Sign Monitoring:** Monitors selected parameters such
  as heart rate, SpO₂, and temperature.
- 📡 **IoT-Based Monitoring:** Uses ESP32 and Raspberry Pi to
  collect and process sensor readings.
- ☁️ **Cloud Data Management:** Uses Google Firebase for storing
  and retrieving patient monitoring information.
- 👨‍⚕️ **Doctor Dashboard:** Provides access to patient details
  and health readings.
- 👪 **Guardian Dashboard:** Helps guardians access relevant
  patient monitoring information.
- 🚨 **Abnormal Reading Alerts:** Identifies readings outside
  configured reference limits.
- 💊 **Medicine Reminders:** Generates reminders according to
  configured medication schedules.
- ⚙️ **Assisted Medicine Dispensing:** Uses a linear actuator
  controlled through Raspberry Pi after manual button activation.
- 🤖 **AI-Assisted Chatbot:** Provides informational assistance
  for medicine-related queries when prescribed medicine is
  unavailable.
- 🖥️ **Local Display:** Displays measurements and instructions
  through an HDMI-connected display.

## 🛠️ Technologies Used

### Hardware
- ESP32 Microcontroller
- Raspberry Pi
- Physiological Sensors
- Temperature Sensor
- Heart Rate and SpO₂ Monitoring Sensors
- GSR Sensor
- Linear Actuator
- Actuator Driver
- Manual Activation Button
- HDMI Display

### Software and Technologies
- Python
- C++ with Arduino Framework
- Google Firebase
- AI Chatbot Integration
- Thonny IDE
- Arduino IDE or compatible development environment

*Note: Include only the components and technologies actually
used in your implementation.*

## ⚙️ System Architecture

The system consists of the following modules:

1. **Patient Monitoring Unit**
   - Collects physiological measurements using sensors.
   - Uses ESP32 for bedside monitoring.

2. **Robotic Monitoring Station**
   - Uses Raspberry Pi for sensor processing and local interaction.
   - Displays patient measurements and instructions.

3. **Cloud Data Management**
   - Transfers monitoring information to Google Firebase.
   - Supports retrieval of patient information by the dashboard.

4. **Doctor and Guardian Dashboards**
   - Present patient details and monitoring information.
   - Support remote observation of available health readings.

5. **Medicine Assistance Module**
   - Provides scheduled medication reminders.
   - Controls the dispensing mechanism after manual activation.

6. **AI-Assisted Chatbot**
   - Provides informational support for medicine-related queries.
   - Does not replace professional medical advice.

## 🔄 Working Principle

1. Sensors collect the patient's physiological measurements.
2. ESP32 or Raspberry Pi processes readings from its connected
   monitoring sensors.
3. Monitoring information is transmitted to Google Firebase
   through the configured network connection.
4. Doctor and guardian dashboards retrieve available
   patient information.
5. The system checks readings against configured reference limits
   and generates alerts when required.
6. The chatbot provides informational assistance for medicine-
   related queries.
7. At a scheduled medication time, the system generates a reminder.
8. The user presses the designated button to activate the
   linear actuator and operate the medicine dispensing mechanism.

## 🎯 Project Objectives

- Develop an IoT-based patient monitoring system.
- Monitor selected physiological parameters.
- Enable cloud-based storage and retrieval of health information.
- Provide doctor and guardian dashboards.
- Identify abnormal readings using configured reference limits.
- Support medication reminders and assisted dispensing.
- Integrate an AI-assisted medicine information chatbot.
- Improve access to patient monitoring information.

## 📸 Project Screenshots

Add photographs of your actual prototype and screenshots of your
implemented dashboards here.

<!-- Add your project images below -->

<!-- Example:
![Smart Robo Nurse Prototype](images/robo-nurse.jpg)
![Patient Monitoring Dashboard](images/dashboard.png)
-->

## 🚀 Installation and Setup

### Prerequisites
- Python
- Required Python libraries
- Firebase project configuration
- Hardware components for the complete prototype

### Steps
1. Clone this repository.
2. Open the project folder.
3. Install the dependencies listed in `requirements.txt`,
   if provided.
4. Configure Firebase credentials securely.
5. Connect the required hardware components.
6. Run the application using the appropriate commands.

Refer to the source code and configuration files for the exact
installation commands and dependencies.

## 🔮 Future Enhancements

- Improve sensor accuracy and fault detection.
- Add medicine-presence and dispensing confirmation sensors.
- Enhance patient data security and access control.
- Improve notification delivery and alert prioritization.
- Integrate a verified medicine information source.
- Add offline data storage and synchronization.
- Improve the mechanical dispensing mechanism.
- Conduct further usability and safety testing.

## ⚠️ Disclaimer

Smart Robo Nurse is a healthcare assistance prototype and is not
a replacement for professional medical care.

Sensor readings require appropriate validation. Medication
alternatives and dosage decisions must be verified by a qualified
healthcare professional.

## 👩‍💻 Project Information

**Project Title:** Smart Robo Nurse for Post-Surgery Patients

**Domain:** IoT, Healthcare, Embedded Systems, Robotics, and
AI-Assisted Applications

**Department:** Information Science and Engineering

**Institution:** Jawaharlal Nehru New College of Engineering
(JNNCE), Shivamogga, Karnataka

## 📄 License

Add a suitable open-source license if you intend to publish the
project under specific reuse terms.
