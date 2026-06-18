# Greek University Admission Calculator (Desktop App)

A complete offline desktop application built with **Java** and **MySQL** that allows candidates of the Greek Panhellenic Exams to calculate their admission points, filter university departments, and view statistical data.

## 🌟 Features
* **Accurate Point Calculation:** Calculates total admission points based on the user's grades and the specific weight coefficients of each department.
* **User Authentication:** Secure registration and login system utilizing password hashing.
* **Advanced Filtering & Search:** Filter departments by city, base points (ascending/descending), and name.
* **Favorites Management:** Users can save and manage their preferred university departments.
* **Data Visualization:** Displays statistical data and charts for different scientific fields using JFreeChart.

## 💻 Tech Stack
* **Language:** Java
* **GUI Framework:** Java Swing
* **Build Tool:** Maven
* **Database:** MySQL (phpMyAdmin/XAMPP or MySQL Workbench)
* **Libraries:** MySQL Connector/J, JCommon, JFreeChart
* **Architecture Modeling:** Visual Paradigm (UML), Figma (UI Mockups)

## 🚀 Installation & Setup Instructions

To run this application locally on your machine, follow these steps:

### 1. Database Setup
1. Ensure you have a MySQL server running (e.g., via **XAMPP** or **MySQL Workbench**).
2. Open your MySQL client and create a new connection.
3. Locate the `panell.sql` file provided in the `database` folder of this repository.
4. Open the SQL script in your client and **Execute** it. This will automatically create the required database schema and insert all the university data.

### 2. Application Setup (via Eclipse IDE)
1. Clone this repository and extract the source code.
2. Open Eclipse and navigate to `File` -> `Import...` -> `Existing Maven Projects`.
3. Select the project directory (`aeitei_uom`) and import it. *(Allow a few moments for Maven to automatically download the required dependencies like JFreeChart)*.
4. Open the `DBConnection.java` file (or wherever your connection class is). 
5. Locate the `PASSWORD` variable and update it with your local MySQL password. *(Note: If you are using XAMPP, the default password is usually empty `""`)*.
6. Right-click on `Main.java` and select **Run As -> Java Application**.

## 🔑 Default Test Credentials
You can create a new account or use the pre-configured test account to explore the application:
* **Email:** `user@example.com`
* **Password:** `test`

## 📸 Screenshots
*(Add a few screenshots of your application here to show the UI)*
