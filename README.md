# Week-2 Week 2 Project: Smart IoT-Enabled Cattle Health and Location Monitoring System using Raspberry Pi

The Week 2 extension of the AI-powered cattle identification project introduces IoT-based health and location monitoring to build a complete smart-farming solution. The system integrates multiple sensors with a Raspberry Pi to automatically identify, monitor, and analyze cattle in real time.

Each animal is tagged with an RFID module (RC522) for unique identification. The GPS module (Neo-6M) continuously tracks the cattle’s location, while DHT11 or DHT22 sensors measure environmental parameters such as temperature and humidity. The Raspberry Pi camera captures images of cattle, which are processed using a pre-trained deep learning model to recognize the breed among 50 officially recognized Indian breeds.

All sensor readings and AI predictions are transmitted to the cloud using ThingSpeak or Firebase, creating a centralized online database for farmers and researchers. This allows real-time visualization of cattle health, environmental conditions, and geographical position through a user-friendly dashboard. The system can generate alerts when abnormal temperature or humidity levels are detected, enabling early intervention in health-related issues.

This Week 2 project demonstrates how AI, IoT, and cloud computing can converge to improve livestock management, breed conservation, and sustainable agriculture. The system provides a low-cost, scalable solution suitable for rural applications and research, offering farmers data-driven insights to enhance productivity, ensure animal welfare, and promote efficient resource utilization.
