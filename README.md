# COVID-19 Health and Authentication System

## Description
The **COVID-19 Health and Authentication System** is a desktop application designed to ensure safety and security in controlled access environments while addressing the challenges posed by the COVID-19 pandemic. This project combines advanced technologies to verify the identity and health status of individuals before granting access, with a specific focus on health monitoring.
Please download the dataset from kaggle with this link https://www.kaggle.com/datasets/spandanpatnaik09/face-mask-detectormask-not-mask-incorrect-mask
## Key Functionalities

1. **QR Code Authentication:**
   - The application utilizes QR code technology to verify a person's identity based on their unique ID.
   - It checks the authenticity of the individual by validating the QR code against a database of authorized users.

2. **Face Mask Detection:**
   - Incorporating a deep learning model, the system checks whether the person is wearing a face mask or not.
   - It ensures adherence to safety guidelines, especially in areas where face coverings are mandatory.

3. **Temperature Measurement:**
   - An Arduino-based temperature sensor is integrated to measure the individual's body temperature.
   - Abnormal temperature readings are flagged as potential health risks.

## Workflow
1. When an individual presents a QR code, the application scans and verifies it against a secure database.
2. Simultaneously, a camera captures an image to assess the presence of a face mask using a trained deep learning model.
3. The individual's body temperature is measured via the Arduino temperature sensor.
4. If all conditions are met (valid QR code, wearing a face mask, normal temperature), access is granted.
5. In case of any discrepancy, access is denied, and an alert is generated.

## Technologies Used
- Python for QR code processing, face mask detection (using OpenCV and TensorFlow), and application logic.
- Deep Learning for the face mask detection model.
- Arduino for temperature measurement with sensors.
- User-friendly GUI using relevant libraries (e.g., C#,Window forms).

## Benefits
- Enhanced security by verifying the identity of individuals.
- Ensures adherence to COVID-19 safety guidelines through face mask detection.
- Early detection of potential health risks through temperature monitoring.
- Seamless integration of hardware and software components.

## Applications
- Access control in secure environments, such as offices, hospitals, airports, and public transportation, with a specific focus on COVID-19 safety measures.
- Compliance monitoring in healthcare facilities and public spaces during the pandemic.
- Contactless and efficient authentication and health screening to mitigate the spread of COVID-19.

## Conclusion
The **COVID-19 Health and Authentication System** demonstrates a comprehensive approach to access control and health monitoring, particularly during the COVID-19 pandemic. It combines cutting-edge technologies to enhance security and safety while addressing the unique challenges posed by the virus. This project showcases my skills in software development, machine learning, and hardware integration, emphasizing my commitment to creating innovative solutions for real-world challenges during these challenging times.
