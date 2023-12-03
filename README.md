# Weather Prediction System with IoT and Machine Learning

## Overview

This project leverages IoT sensors and machine learning algorithms to predict future weather conditions based on both current and historical data. By combining real-time sensor data with advanced machine learning techniques, the system aims to provide accurate and timely weather predictions.

## Key Features

- **IoT Integration**: The system incorporates IoT sensors to gather current weather data, ensuring real-time inputs for accurate predictions.

- **Machine Learning Algorithms**: We employ state-of-the-art machine learning algorithms to analyze both current and historical data, allowing the system to learn patterns and trends for precise weather forecasting.

- **Predictive Modeling**: The core of the system involves building predictive models that consider various meteorological factors to forecast future weather conditions.

- **User-Friendly Interface**: The project provides a user-friendly interface to input specific parameters, visualize predictions, and explore historical data.

## How It Works

1. **Data Collection**: IoT sensors collect real-time weather data such as temperature, humidity, and atmospheric pressure.

2. **Data Processing**: The collected data is processed to remove noise and ensure data integrity. Historical data is also integrated into the analysis.

3. **Machine Learning Training**: The system trains machine learning models using historical data to recognize patterns and relationships between different weather parameters.

4. **Prediction Generation**: The trained models are then used to predict future weather conditions based on the current input from IoT sensors.

5. **User Interaction**: Users can interact with the system through an intuitive interface to input specific parameters, view predictions, and explore historical weather patterns.

## Getting Started

To run the Weather Prediction System on your local machine, follow these steps:

1. **Clone the Repository**:
   ```
   git clone https://github.com/your-username/Weather-Prediction-Using-IOT-and-ML.git
   ```

2. **Install Dependencies**:
   ```
   cd Weather-Prediction-Using-IOT-and-ML

   pip install -r requirements.txt
   ```

3. **Run the System**:
   ```
   python app.py
   ```


## Technologies Used

- Python
- Thingspeak
- Flask
- IoT sensors (DHT11, BMP180, Rainsensor, NodeMCU ESP8266, BreadBoard)
