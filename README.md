# Blood Bank Management System

## Overview
The Blood Bank Management System is a platform that allows for the management of blood donations and requests. The system is designed to streamline blood donation processes, monitor the status of donations and requests, and facilitate communication between donors, patients, and admins. It provides an intuitive interface to track blood groups, donation histories, and approval/rejection statuses.

## Features
### Admin
- **Admin Account Creation**: Create an admin account using the command:
    ```bash
    py manage.py createsuperuser
    ```
- **Dashboard**: View blood units available for each blood group, the number of donors, blood requests, approved requests, and total blood stock.
- **Donor Management**: View, update, and delete donor records.
- **Patient Management**: View, update, and delete patient records.
- **Donation Request Management**: Approve or reject donation requests based on the donor's health status. If approved, the blood unit is added to the respective blood group stock. If rejected, no units are added.
- **Blood Request Management**: Approve or reject blood requests made by patients or donors. If approved, blood units are deducted from the respective blood group stock. If rejected, no units are deducted.
- **History Tracking**: View the history of all blood requests and donations.
- **Blood Group Management**: Update the units of any particular blood group.

### Donor
- **Donor Registration**: Donors can create accounts by providing basic information.
- **Blood Donation**: After admin approval, blood donations are added to the blood stock.
- **Donation History**: Donors can view their donation history along with its status (Pending, Approved, Rejected).
- **Blood Request**: Donors can request blood from the available stock.
- **Request History**: Donors can view their blood request history and its status.
- **Dashboard**: Donors can track the number of blood requests they have made, along with their approval/rejection status.

### Patient
- **Patient Registration**: Patients can create accounts without admin approval and log in immediately.
- **Blood Request**: Patients can request blood from the available stock, specifying the blood group and unit.
- **Request History**: Patients can view the status (Pending, Approved, Rejected) of their blood requests.
- **Dashboard**: Patients can see the number of blood requests made, approved, pending, and rejected.

## Screenshots
### Homepage
![homepage snap](https://github.com/sumitkumar1503/bloodbankmanagement/blob/master/static/screenshot/homepage.png?raw=true)

### Admin Dashboard
![dashboard snap](https://github.com/sumitkumar1503/bloodbankmanagement/blob/master/static/screenshot/admindashboard.png?raw=true)

### Blood Donation
![invoice snap](https://github.com/sumitkumar1503/bloodbankmanagement/blob/master/static/screenshot/blooddonation.png?raw=true)

### Blood Request
![doctor snap](https://github.com/sumitkumar1503/bloodbankmanagement/blob/master/static/screenshot/bloodrequest.png?raw=true)

### Logout
![doctor snap](https://github.com/sumitkumar1503/bloodbankmanagement/blob/master/static/screenshot/logout.png?raw=true)

## Requirements
- Python 3.7.6 or later
- Django

## Installation

1. Install Python 3.7.6 (ensure you check the "Add to PATH" option during installation).
2. Download the project ZIP folder and extract it.
3. Open your terminal and navigate to the project directory.
4. Install the necessary dependencies:
    ```bash
    python -m pip install -r requirements.txt
    ```
5. Run database migrations:
    ```bash
    py manage.py migrate
    ```
6. Start the development server:
    ```bash
    py manage.py runserver
    ```
7. Open your browser and go to the following URL to access the system:
    ```
    http://127.0.0.1:8000/
    ```

## Acknowledgements
- This project was developed by Aman Kumar Bhati as part of the Blood Bank Management System.
