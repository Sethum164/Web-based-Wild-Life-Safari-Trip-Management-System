# 🦁🌿 Wildlife Safari Trip Management System

[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.java.com/)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)](https://spring.io/projects/spring-boot)
[![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)

> **A modern, web-based system to manage safari trip operations efficiently.**

## 📘 About the Project

The **Wildlife Safari Trip Management System** is a comprehensive full-stack web application designed to digitalize and streamline wildlife safari operations. It replaces traditional manual processes with a centralized digital platform, simplifying trip bookings, vehicle and guide allocation, payment tracking, and feedback management.

This system facilitates smooth coordination between staff, management, and customers, ensuring real-time data availability and efficient decision-making.

### 🌍 Key Impacts
* **Enhanced Customer Experience:** Seamless online booking reduces wait times.
* **Operational Efficiency:** Automated workflows minimize human error.
* **Resource Optimization:** Real-time tracking of vehicles and guides.
* **Data Security:** Centralized records prevent data loss.

---

## 🚀 Features

### 👥 User Roles
The system supports a secure multi-role login system for the following stakeholders:
* **Admin:** Manage users, system settings, and overall operations.
* **Customer:** Book safari trips and provide feedback.
* **Vehicle Coordinator:** Manage vehicle registration, availability, and maintenance.
* **Guide:** View and manage assigned safari trips.
* **Operations Manager:** Oversee trip scheduling, vehicles, and guides.
* **Finance Personnel:** Handle payments, invoices, and refunds.

### 🛠 System Modules
* 🗓️ **Trip Booking & Reservation:** streamlined booking interface.
* 🚗 **Vehicle Assignment:** Maintenance tracking and allocation.
* 🧑‍🏫 **Guide Scheduling:** Roster management and conflict resolution.
* ⭐ **Customer Feedback:** Collection and reporting for service improvement.
* 💳 **Finance Management:** Payment tracking, invoicing, and refund approvals.

---

## 🧰 Tech Stack

| Component | Technology |
| :--- | :--- |
| **Backend** | Java, Spring Boot |
| **Frontend** | HTML, CSS, Bootstrap, JavaScript, JSP |
| **Database** | MySQL (via XAMPP) |
| **Build Tool** | Maven |
| **Version Control** | Git & GitHub |

---

## 💻 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
* [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/downloads/) (Version 8 or higher)
* [Maven](https://maven.apache.org/)
* [XAMPP](https://www.apachefriends.org/index.html) (or any MySQL server)

### Installation

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/your-username/wildlife-safari-system.git](https://github.com/your-username/wildlife-safari-system.git)
    ```
2.  **Configure the Database**
    * Open XAMPP and start Apache and MySQL.
    * Create a new database named `safari_db` (or check `application.properties` for the exact name).
    * Import the SQL script located in `/src/main/resources/db` (if provided) or allow Hibernate to auto-generate tables.
3.  **Configure Application Properties**
    * Navigate to `src/main/resources/application.properties`.
    * Update your MySQL username and password:
        ```properties
        spring.datasource.url=jdbc:mysql://localhost:3306/safari_db
        spring.datasource.username=root
        spring.datasource.password=your_password
        ```
4.  **Build and Run**
    ```bash
    mvn clean install
    mvn spring-boot:run
    ```
5.  **Access the Application**
    * Open your browser and navigate to: `http://localhost:8080`

---

## 👨‍💻 Module Ownership & Team

This project was developed collaboratively with specific module ownership:

| Team Member | Module Responsibility |
| :--- | :--- |
| **Rivi** | Trip Booking Management |
| **Devindi** | Vehicle Assignment System |
| **Kanishka** | Guide Scheduling System |
| **Illham** | Customer Feedback Collection |
| **Thisul** | Vehicle Registration & Management |
| **Praveen** | Payment Tracking & Approval |

---

## 🎯 Learning Outcomes

This project served as a practical application of:
* Full-stack web application development.
* MVC architecture and RESTful API concepts.
* Real-world system workflows and constraint management.
* Agile-based teamwork and collaboration.

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  ⭐ If you find this project useful, please consider giving it a star on GitHub! ⭐
</p>
