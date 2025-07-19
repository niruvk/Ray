# Ray
A Smart UV Tracking Necklace

<img width="1024" height="1024" alt="Ray" src="https://github.com/user-attachments/assets/ebb497fe-0dc6-4142-904c-4db1f974ee4d" />


# Project Description
"Ray" is a wearable technology project that combines fashion with healthcare. This project introduces a necklace that is integrated with a UV sensor capable of tracking UV radiation. Paired with a mobile app hosted using Blynk, "Ray" aims to revolutionize how individuals interact with and manage their sun exposure.

Key Features:
- UV Monitoring: Continuous tracking of UV levels to give real-time and historical data through a chart and value display.
- Harshness Index: UV monitoring technology currently available in the market displays only real-time UV values. However, prolonged UV exposure can be harmful, and existing solutions do not take into account the duration of exposure.Additionally, existing solutions do not account for the application of sunscreen by a user. Our solution utilizes Machine Learning to develop a "Harshness Index". It incorporates a temporal component, hence, considers both the time of exposure and the level of UV radiation. Additionally, our project takes in user input about the SPF applied. Based on this data, it makes personalized suggestions to users to increase or decrease their sun exposure.
- SPF Recommendations: Intelligent algorithm that suggests suitable SPF protection based on the current UV index, and user-inputted value of SPF applied.
- Skin Cancer Likelihood: Incorporates machine learning to predict how much more or less likely the user is to develop skin cancer based off historical raw UV data
- Sun Intensity Alerts: Push notifications to warn users of high UV levels and advise on protective measures.
- User-friendly App Interface: Easy-to-navigate app providing a seamless user experience for monitoring and managing sun exposure data.

Technical Specifications:
- UV sensor technology.
- ESP8266 for data collection and processing.
- WiFi connectivity for seamless data transfer to the mobile app.
- Battery with easy charging options for power.
- Wires for connection between peripherals.
  <img width="949" alt="image" src="https://github.com/niruvk/Ray/assets/107680271/f61bad0b-b1da-45b3-89aa-2a5268c2ed44">
<img width="946" alt="image" src="https://github.com/niruvk/Ray/assets/107680271/6ec9044c-54d6-43b4-845d-4d5b64dfa1ca">


# Installation
- Download the DataProcessor.py, .txt, and .csv files
- Run DataProcessor continuously on a server
- Upload blynk_setup.ino onto ESP8266 connected with VEML6070 and battery
- Configure Blynk App to collect and showcase data however desired
- Replace redacted information with personal information

# End Product
- User will download an app and receive hardware (necklace) with an easy setup and connection

# Credits
- Divija Durga (divija@princeton.edu)
- Niranjan Vijaya Krishnan (niruvk@princeton.edu)

Created for HackPrinceton 2023
