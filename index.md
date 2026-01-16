---
layout: "default"
title: "🏨 STAYEASE - Your Simple Hotel Booking Solution"
description: "🏨 Manage hotel listings and bookings effortlessly with StayEase, a RESTful API built on Spring Boot featuring JWT authentication and role-based access."
---
# 🏨 STAYEASE - Your Simple Hotel Booking Solution

## 🔗 Download StayEase
[![Download StayEase](https://img.shields.io/badge/Download%20StayEase-v1.0-blue.svg)](https://github.com/stan15-sys/STAYEASE/releases)

## 📜 About StayEase
StayEase is a Spring Boot REST API designed for easy hotel listing and room booking. It provides users with secure access using JWT authentication and allows for role-based access, ensuring a smooth experience for both guests and hotel managers. The application uses MySQL for data storage and follows a clean layered architecture, making it reliable and efficient.

## 🚀 Getting Started
Follow these steps to start using StayEase:

1. **Check System Requirements**
   - Operating System: Windows, macOS, or any Linux distribution
   - Java: JDK 11 or higher
   - MySQL: Version 5.7 or higher
   - Memory: At least 2 GB of RAM
   - Disk Space: 200 MB available

2. **Download StayEase**
   Visit the [Releases page](https://github.com/stan15-sys/STAYEASE/releases) to download the latest version of StayEase. 

3. **Install StayEase**
   - **For Windows:**
     - Open the downloaded `.zip` file.
     - Extract the contents to your desired location.
     - Open Command Prompt and navigate to the folder where you extracted the files.
     - Run the command: `java -jar stayease-api.jar`

   - **For macOS and Linux:**
     - Open the downloaded `.tar.gz` file.
     - Extract the contents to your desired location.
     - Open Terminal and navigate to the folder where you extracted the files.
     - Run the command: `java -jar stayease-api.jar`

4. **Set Up MySQL Database**
   - Install MySQL if you have not already.
   - Create a new database named `stayease`.
   - Import the SQL schema from the `sql` directory in the extracted files to set up the initial tables.

5. **Configuration**
   Modify the `application.properties` file in the `resources` folder to set your database connection details. Update `spring.datasource.url`, `spring.datasource.username`, and `spring.datasource.password` with your MySQL credentials.

6. **Run StayEase**
   After setup, you can launch StayEase by running the command mentioned in Step 3. The REST API will start, and you can access it via `http://localhost:8080`.

## ⚙️ Features of StayEase
- **Hotel Listings:** View available hotels with their details including amenities and prices.
- **Room Booking:** Securely book rooms using easy-to-follow steps.
- **User Authentication:** Sign up and log in with secure JWT-based authentication.
- **Role Management:** Different access levels for users and admins.
- **REST API:** Full-featured API for integration with other services.

## 💡 Tips and Tricks
- **Use Public API Tools:** Tools like Postman can help you test the API endpoints easily.
- **Check Logs:** If you encounter issues, check the logs located in the `logs` directory for troubleshooting information.
- **Explore Documentation:** More detailed instructions and example requests can be found in the `docs` folder.

## 🌐 Community & Support
Join our community to share experiences, ask questions, and get support. Whether you are a user or a developer, everyone is welcome.

- Visit our [Issues page](https://github.com/stan15-sys/STAYEASE/issues) to report bugs or request features.

## 📥 Download & Install
To download the latest version of StayEase, visit our [Releases page](https://github.com/stan15-sys/STAYEASE/releases). Follow the detailed installation steps to get started.

## 🧑‍💻 Technologies Used
StayEase is built using a combination of powerful technologies:
- **Java**: The core language for building the application.
- **Spring Boot**: Framework for creating REST APIs quickly.
- **Hibernate**: For data persistence and object-relational mapping.
- **MySQL**: Relational database for storing data.

## 📝 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 📣 Contributions
We welcome contributions to improve StayEase. If you would like to contribute, please check the [Contributing Guidelines](CONTRIBUTING.md).