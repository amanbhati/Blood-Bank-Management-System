# 💉 Blood Bank Management System

## 📖 Overview
The **Blood Bank Management System** is an intuitive platform designed to optimize the process of managing blood donations and requests. This system connects donors, patients, and administrators, providing a seamless flow of blood donation data and real-time updates on available blood units. It ensures efficient blood management, tracks donations, and keeps records of donation and blood request statuses.

Whether you're a **donor**, a **patient**, or an **admin**, the system ensures all blood-related tasks are easy, fast, and well-organized.

---

## 🚀 Key Features

### Admin Features:
- **Admin Account Creation**: Easily create an admin account with the following command:
    ```bash
    py manage.py createsuperuser
    ```
- **Comprehensive Dashboard**: Admin can view an overview of:
    - Blood units available for each group
    - Number of donors and blood requests
    - Blood stock status and approved requests
- **Manage Donors**: View, update, or delete donor records with ease.
- **Manage Patients**: View, update, or delete patient information.
- **Donation Request Handling**: Approve or reject donation requests based on donor health. Approved donations add units to the blood stock.
- **Blood Request Handling**: Manage and approve blood requests from patients and donors. Approved requests deduct units from the available stock.
- **History Tracking**: Track donation and blood request histories to monitor overall activity.
- **Blood Group Management**: Update blood unit counts for each blood group.

### Donor Features:
- **Donor Registration**: Simple sign-up process for donors by providing basic details.
- **Blood Donation**: Donate blood, and once approved by the admin, your donation is added to the blood stock.
- **Donation History**: View a detailed history of your blood donations with status updates (Pending, Approved, Rejected).
- **Blood Request**: Donors can request blood from the available stock.
- **Request History**: Track the status of your blood requests (Pending, Approved, Rejected).
- **Dashboard**: See your donation and request stats in one glance.

### Patient Features:
- **Easy Patient Registration**: Create an account without admin approval and get instant access.
- **Blood Request**: Request blood from the available stock, specifying the blood group and quantity required.
- **Request History**: View the status of your blood requests (Pending, Approved, Rejected).
- **Dashboard**: Track the number of requests made, and their approval/rejection status.

---

## 📸 Screenshots

### Homepage
![homepage snap](https://github.com/sumitkumar1503/bloodbankmanagement/blob/master/static/screenshot/homepage.png?raw=true)

### Admin Dashboard
![dashboard snap](https://github.com/sumitkumar1503/bloodbankmanagement/blob/master/static/screenshot/admindashboard.png?raw=true)

### Blood Donation
![blood donation snap](https://github.com/sumitkumar1503/bloodbankmanagement/blob/master/static/screenshot/blooddonation.png?raw=true)

### Blood Request
![blood request snap](https://github.com/sumitkumar1503/bloodbankmanagement/blob/master/static/screenshot/bloodrequest.png?raw=true)

### Logout Screen
![logout snap](https://github.com/sumitkumar1503/bloodbankmanagement/blob/master/static/screenshot/logout.png?raw=true)

---

## 🛠️ Requirements
- **Python 3.7.6** or higher
- **Django**

---

## 🏁 Installation Guide

1. **Install Python**: Download and install Python 3.7.6 (ensure to check the "Add to PATH" option during installation).
2. **Download the Project**: Download the ZIP file of this project and extract it.
3. **Install Dependencies**: Open your terminal, navigate to the project directory, and install the required dependencies:
    ```bash
    python -m pip install -r requirements.txt
    ```
4. **Run Database Migrations**: Ensure the database is properly set up:
    ```bash
    py manage.py migrate
    ```
5. **Start the Development Server**: Launch the server to view the project in action:
    ```bash
    py manage.py runserver
    ```
6. **Access the System**: Open your browser and go to:
    ```
    http://127.0.0.1:8000/
    ```

---

## 🙌 Acknowledgements
This project was developed by **Aman Kumar Bhati** as part of the **Blood Bank Management System** initiative. Feel free to contact me for any suggestions, feedback, or questions!

---

**Your contributions and feedback are always welcome!** 🙏
