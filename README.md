# Graduation Project Evaluation System (GPES)

Note: You can find the detailed description of the project in the docx file.
## Overview
The Graduation Project Evaluation System (GPES) is a comprehensive platform designed to modernize and streamline the evaluation process for academic graduation projects. By integrating advanced technologies and innovative design principles, GPES aims to overcome the limitations of traditional assessment methods, enhancing efficiency, fairness, and accountability in academic workflows.

## Features

### 1. **Web and Mobile Integration**
   - **Web Platform**: A robust and scalable platform built using .NET Framework to facilitate project submission, evaluation, and feedback.
   - **Mobile Application**: Developed with Flutter and Dart, offering a high-performance, cross-platform solution for professors to assess and track project progress seamlessly.

### 2. **Role-Based Access Control**
   - **Students**: Submit projects, view assigned presentation slots, and receive feedback.
   - **Professors**: Evaluate projects, manage schedules, and provide feedback.
   - Role assignments and access permissions are securely managed through SQL Server Management Studio.

### 3. **Automated Scheduling**
   - **Presentation Scheduling**: Utilizes an optimized backtracking algorithm to assign teams to available time slots based on professor availability.
   - **Error Handling**: Ensures robustness by retrying scheduling for teams that could not be initially assigned.
   - **Combination Generation**: Automates the selection of professor combinations for each team’s presentation.

### 4. **Database Management**
   - **SQL Server**: Handles robust data storage and retrieval, supporting project submissions, professor availability, and user information.
   - Key tables:
     - `AvailableDateTimeSlot`: Tracks professor availability.
     - `BookedDates`: Records scheduled presentations.
     - `Projects`: Stores project details.
     - `Professors`: Manages professor profiles and schedules.

### 5. **Onion Architecture**
   - Promotes modularity, scalability, and maintainability by separating business logic from infrastructure layers.
   - Ensures testability and ease of future enhancements.

### 6. **Enhanced Authentication**
   - **Web Login**: Secure login process leveraging Selenium for automated portal access.
   - **Mobile Authentication**: API-driven authentication, ensuring consistent user experience across platforms.

### 7. **API Documentation and Testing**
   - **Swagger**: Facilitates detailed API documentation and seamless communication between web and mobile platforms.
   - Simplifies API integration and testing for developers.

### 8. **Synchronization Endpoint**
   - Ensures synchronization of user-professor relationships, automatically adding missing mappings for consistency.

## Technologies Used
- **Flutter & Dart**: For cross-platform mobile application development.
- **.NET Framework**: Backend development for the web application.
- **SQL Server Management Studio (SSMS)**: Database management and user role control.
- **Swagger**: API documentation and testing.
- **Postman**: API testing and debugging.
- **Selenium**: Automates web portal interactions for user authentication.

## How It Works
1. **Authorization**
   - Users log in using credentials verified against the school’s information system.
   - Role-based access ensures secure and appropriate resource usage.

2. **Project Submission and Scheduling**
   - Students submit projects through the web platform.
   - Scheduling algorithms assign presentation slots efficiently.

3. **Evaluation**
   - Professors evaluate projects via the mobile app or web platform.
   - Feedback is provided to students through the system.

## Benefits
- **Efficiency**: Reduces manual intervention in scheduling and evaluation.
- **Transparency**: Ensures clarity in scheduling and assessment processes.
- **Accessibility**: Cross-platform support enables usage from any device.
- **Scalability**: Designed to accommodate growing user and data demands.
- **Security**: Role-based access control and secure data handling.

## Future Enhancements
- Integration of advanced analytics for performance insights.
- Support for additional languages to cater to a global audience.
- Enhanced reporting capabilities for stakeholders.

## Conclusion
GPES is a cutting-edge solution that transforms the traditional graduation project evaluation process. By leveraging modern technologies and a user-centric design approach, it facilitates a seamless experience for students and professors, ensuring efficiency, fairness, and accountability in academic evaluations.

