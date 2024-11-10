# Mobile Application to View Live Count and History of a Counting Device

This repository contains the implementation of a **PowerApps mobile application** that allows users to view the **live count** and **history** of a counting device. The counting device is integrated with **IoT sensors** and an **ESP32** microcontroller to collect and transmit data to **cloud storage**.

## Features

- **Live Count Display:** The mobile app shows the current live count data received from the counting device.
- **History Tracking:** Users can view the historical count data stored in cloud storage.
- **Cloud Integration:** The system stores and retrieves count data using cloud storage, enabling persistent access to historical data.
- **PowerApps Integration:** The app is built using PowerApps, allowing for a low-code approach to app development and easy integration with cloud services and IoT devices.

## Technologies Used

- **PowerApps:** For building the mobile application and creating a user-friendly interface.
- **ESP32:** A microcontroller that integrates with sensors to collect count data and send it to the cloud.
- **IoT Sensors:** For detecting events (e.g., objects passing by a sensor) and generating count data.
- **Cloud Storage (e.g., Azure, Google Cloud, or AWS):** For storing and retrieving the count history.
- **Power Automate (Optional):** For automating data flow between the ESP32, cloud storage, and PowerApps.

## Setup

### Hardware Setup:
1. **ESP32** with integrated IoT sensors.
2. Set up the ESP32 to send count data to cloud storage (e.g., Firebase, Azure, or Google Cloud).

### PowerApps Setup:
1. Clone this repository to your local machine.
2. Open PowerApps and create a new app using the provided template or connect to the cloud storage where the count data is stored.
3. Set up the PowerApps components to fetch the live count data and historical data from the cloud storage.
4. Customize the app to meet specific requirements (e.g., layout, data display, etc.).
5. Test the app on your mobile device.

### Cloud Storage Setup:
1. Set up the cloud storage to receive data from the ESP32.
2. Make sure that the cloud storage can store both live count and historical data.
3. Configure cloud storage to allow access from PowerApps.

