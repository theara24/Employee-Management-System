# 🏛️ Civil Management System (C++)

The **Civil Management System** is a C++ console application developed to efficiently manage civil servant data. The system is divided into two main roles: **Admin** and **User**, each offering role-specific features such as data management, attendance tracking, salary calculation, and reporting.

---

## 📌 Features

### 👨‍💼 Admin Panel
Admins have full control over the system and can perform the following operations:

- **Add Civil Servants**: Register new civil servants with all necessary details.
- **View Civil Servants**: Display all registered civil servant records.
- **Sort Civil Servants**: Sort by name, ID, or department.
- **Search Civil Servants**: Search records by keyword.
- **Update Civil Servants**: Modify existing civil servant data.
- **Delete Civil Servants**: Remove civil servant records from the system.
- **Attendance & Time Management**: Record attendance and calculate work hours.
- **Salary Calculation**: Automatically compute salary based on hours worked and attendance.
- **Generate Reports**: Create attendance and salary reports.
- **Return to Main Menu**: Navigate back to the registration menu.

---

### 👤 User Panel
Users have access to the following features:

- **View Civil Servants**: View the list of all civil servants.
- **Sort Civil Servants**: Sort based on name, ID, or department.
- **Search Civil Servants**: Quickly find a civil servant using a keyword.
- **Attendance & Time View**: Check attendance and recorded working hours.
- **Salary Overview**: View calculated salary based on attendance data.
- **Reporting**: Access attendance and salary reports.
- **Return to Login**: Navigate back to the login page.

---

## 🛠️ Technologies Used

- **C++ Programming Language**
- **DEV C++** IDE
- **Binary File Handling** for persistent data storage

---

## 📂 Project Structure

```bash
CivilManagementSystem/
├── main.cpp
├── admin/
│   ├── AddCivilServant.cpp
│   ├── ViewCivilServant.cpp
│   └── ...
├── user/
│   ├── ViewCivilServant.cpp
│   ├── AttendanceView.cpp
│   └── ...
├── data/
│   ├── civil_servants.dat
│   └── attendance.dat
├── utils/
│   ├── sorting.cpp
│   ├── searching.cpp
│   └── ...
├── README.md
