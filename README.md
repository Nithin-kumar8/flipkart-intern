# flipkart-intern#
Employee Leave Management System (ELMS)

## Overview
The Employee Leave Management System (ELMS) is a comprehensive web application designed to streamline and automate the process of managing employee leave requests. It provides features for employees to request leave, managers to approve/reject requests, and administrators to manage the system and generate reports.

## Features
- **User Authentication**: Secure login for employees, managers, and administrators
- **Leave Request Management**: Submit, view, and track leave requests
- **Approval Workflow**: Managers can approve/reject pending leave requests
- **Leave Balance Tracking**: Automatic tracking of available leave days
- **Reporting**: Detailed reports on leave trends and department statistics
- **Admin Dashboard**: Comprehensive system management tools
- **Responsive Design**: Works on desktop and mobile devices

## Technology Stack
- **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5
- **Backend**: Python, Flask
- **Database**: SQLite (with SQLAlchemy ORM)
- **Authentication**: Flask-Login
- **Charts**: Chart.js

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Nithin-kumar8/flipkart-intern.git
   cd elms
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:
   ```bash
   python app.py
   ```

5. Access the application at `http://127.0.0.1:5000
## Usage
### Login Credentials
- **Admin**: username `admin`, password `admin123`
- **Employee**: username `employee`, password `emp123`
- **Manager**: username `manager`, password `man123`

### Employee Features
- View leave balances
- Submit new leave requests
- Track request status
- View request history

### Manager Features
- Approve/reject leave requests
- View team leave calendar
- Monitor pending approvals

### Admin Features
- Manage all users
- Configure leave types
- Generate system reports
- Monitor system activity

## Screenshots
### Login page
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/a9f446f2-23e3-417a-8d7e-d3b29002fbf1" />
