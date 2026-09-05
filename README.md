# Staff Attendance Register


## Institution

**Global Degree College**
**Jagdish Krishna Educational Society**
Bhiwandi, Maharashtra, India

**Academic Year:** 2026–27

---

## Overview

The Staff Attendance Register provides a structured digital interface for maintaining staff attendance throughout the academic year.

It is designed to combine the simplicity of a traditional physical attendance register with the convenience of a modern web-based system.

The system supports:

* Staff master information
* Daily attendance
* Monthly attendance tracking
* Attendance summaries
* Leave and On-Duty records
* Annual attendance summaries
* Attendance percentage calculation
* Institutional verification
* Print-ready reports

---

## Key Features

### Staff Management

* Add and manage staff members
* Employee ID
* Staff name
* Designation
* Department
* Joining date
* Employment type
* Staff signature reference

### Attendance Management

Attendance can be recorded using:

| Code | Meaning  |
| ---- | -------- |
| P    | Present  |
| A    | Absent   |
| L    | Leave    |
| OD   | On Duty  |
| HD   | Half Day |

### Monthly Attendance

The system provides attendance records for the complete academic year:

* April
* May
* June
* July
* August
* September
* October
* November
* December
* January
* February
* March

The system also handles the correct number of days for each month.

### Attendance Summary

Monthly summaries include:

* Working Days
* Present
* Absent
* Leave
* On Duty
* Half Day
* Attendance Percentage

### Leave / On-Duty Record

Maintain institutional records for:

* Leave
* Official Duty
* Date
* Duration
* Reason / Purpose
* Approval
* Remarks

### Annual Summary

The annual section provides an overview of staff attendance across the complete academic year.

---

## Print-Ready Design

The system is designed specifically for institutional printing.

It supports:

* A4 paper
* Print-friendly layouts
* Proper page breaks
* Institutional headers
* Footers
* Page numbering
* Signature areas
* Principal verification
* Official seal space
* Black-and-white printing

The printed output is designed to resemble a **formal college administrative register**, rather than a conventional web dashboard.

---

## Technology

This project uses a simple client-side technology stack:

* **HTML5**
* **CSS3**
* **JavaScript**
* **Browser LocalStorage**

No backend server is required.

No database installation is required.

No framework is required.

---

## Project Structure

```text
staff-attendance-register/
│
├── index.html
└── README.md
```

If additional assets are introduced later:

```text
staff-attendance-register/
│
├── index.html
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
│
└── README.md
```

---

## How to Use

### 1. Open the Application

Open:

```text
index.html
```

in a modern web browser.

Recommended browsers:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox

### 2. Add Staff

Enter the required staff information in the Staff Master section.

### 3. Record Attendance

Select the appropriate attendance status for each staff member.

### 4. Maintain Monthly Records

Update attendance throughout the academic year.

### 5. Review Summaries

Use the monthly and annual summary sections to review attendance statistics.

### 6. Print

Use the application's print functionality or the browser's print option to generate physical records.

For best results:

**Paper Size:** A4
**Orientation:** As specified by the application
**Margins:** Default / controlled by print CSS
**Scale:** Fit to page where required

---

## Academic Year

The default academic year is:

**2026–27**

The register follows the academic cycle:

**April 2026 → March 2027**

---

## Institutional Use

This system can be adapted for:

* Degree Colleges
* Junior Colleges
* Schools
* Coaching Institutes
* Training Institutes
* Educational Societies
* Academic Departments
* Administrative Offices

It can also be customized for individual departments such as:

* Information Technology
* Computer Science
* Commerce
* Management
* Arts
* Science

---

## Data Storage

The application is designed as a client-side application.

Where LocalStorage is implemented, data is stored in the user's browser.

This means:

* No server is required
* No internet connection is required after loading the application
* Data remains available in the same browser/device
* Browser data should be backed up before clearing browser storage

**Important:** Do not rely on browser storage as the only institutional record. For official records, maintain appropriate backups and physical records according to institutional requirements.

---

## Privacy

This application is intended for institutional administrative use.

Staff information and attendance data should be treated as **internal institutional records**.

If deployed publicly, avoid entering confidential or sensitive information unless appropriate security controls are implemented.

---

## Customization

The system can be customized with:

* College name
* Society name
* Logo
* Academic year
* Departments
* Staff categories
* Attendance codes
* Designation fields
* Signature sections
* Principal details
* Institutional address
* Official seal area

---

## Deployment on GitHub Pages

This project can be hosted using **GitHub Pages** because it is a client-side HTML/CSS/JavaScript application.

Basic deployment:

1. Create a GitHub repository.
2. Upload `index.html`.
3. Upload `README.md`.
4. Open **Settings → Pages**.
5. Select the required branch.
6. Select the root folder.
7. Save the configuration.
8. GitHub Pages will provide the website URL.

---

## Future Enhancements

Possible future improvements include:

* PDF export
* Excel export
* CSV export
* JSON backup and restore
* Multi-user login
* Cloud database
* Role-based access
* Principal dashboard
* Department-wise attendance
* Staff search and filtering
* Attendance analytics
* Automated monthly reports
* Digital signatures
* University/NAAC documentation support

---

## Purpose

The purpose of this project is to provide educational institutions with a **simple, professional, structured and print-ready method of maintaining staff attendance records** while reducing unnecessary manual calculation and documentation effort.

---

## License

This project is intended for educational and institutional administrative use.

Add an appropriate open-source license if you plan to distribute or modify the project publicly.
