# Key Component Traceability System

## Overview
This project addresses the challenges of recording the barcodes of TV set components (e.g., LED bar, PCB, open-cell) in the production process. The project was implemented at the TV factory of **ElAraby Group** to replace the existing Japanese system, **Snoopy**, with a more efficient solution.

## Problem Statement
The Snoopy system, a manual scanner for reading and storing serial numbers in a database, had several significant limitations:

1. **Technician Training**: The manual scanner required technicians to be well-trained to maintain the correct scanning distance.
2. **Low Sensitivity**: The scanner could only read up to 25 digits, ignoring any additional data.
3. **Dependency on Servers**: The system relied on servers. Any server downtime caused production line disruptions for hours, and the system was not customizable.

## Proposed Solution
To overcome these limitations, we developed a mobile application as an alternative. The application utilizes the mobile camera, which offers higher sensitivity compared to the manual scanner. The recorded data is stored in a **Firebase Database** for better security and reliability.

### Key Features of the Solution
1. **Component Scanning**: The mobile application scans barcodes in the production line and stores the data in Firebase.
2. **Search Functionality**: Users can search for components stored in the database.

![Production Line Scanner](image_A.png)

### Video Demonstrations:
- **Video 1**: Demonstrates how the program works as a scanner in the production line.
- **Video 2**: Shows the search functionality for recorded components.

## Extension to Customer Service
We expanded the solution to enhance customer service by developing another application. This application allows customers to:

1. Scan the barcode on their guarantee certificate.
2. Input their personal data and send it to the company.

The customer data is received in a **Google Sheet** connected to the Firebase database.

### Advantages of the Google Sheet Integration:
1. **Component Details**: As soon as the device’s barcode is received, details of its internal components are displayed.
2. **Customer Data Management**: The customer’s data, along with the time and date of submission, is recorded. This helps customer service schedule technician visits.
3. **Response Tracking**: A deadline of four days is set for responding to customer issues:
   - **Green**: Within deadline.
   - **Red**: Exceeded deadline.
   - **Gray**: Issue resolved and closed.

![Google Sheet Integration](image_5.png)

### Video Demonstrations:
- **Video 3**: Demonstrates the customer application and database interaction.
- **Video 4**: Shows how customer data is managed in the Google Sheet.

## Technologies Used
1. **Mobile Application**: For barcode scanning and data entry.
2. **Firebase Database**: A secure and reliable database from Google.
3. **Google Sheets**: For integrating customer service data.

## Team Members
- **Amira Mohamed**
- **Mahmoud Elbasit**
- **Ammar Yasser**
- **Alaa Amin Elgezery**

