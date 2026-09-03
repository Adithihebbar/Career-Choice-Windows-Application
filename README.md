# Career-Choice-Windows-Application
# Career Choice – Windows Recruitment Portal

A desktop-based recruitment management system developed using **C#, .NET Windows Forms, and SQL Server** for managing job postings, candidate registrations, and recruitment workflows.

## Overview

Career Choice is a Windows-based recruitment portal designed to simplify the recruitment process for both administrators and candidates. The application provides separate modules for managing job posts, candidate information, applications, and recruitment activities.

## Features

### Candidate Module

* Candidate registration and login
* View available job openings
* View job details
* Apply for jobs
* Upload required documents
* View application details
* Change password

### Admin Module

* Admin login
* Add and manage job postings
* View candidate registrations
* View applications
* Manage recruitment-related information
* Change admin password
* View application and candidate reports

## Technology Stack

* **Language:** C#
* **Framework:** .NET Windows Forms
* **Database:** Microsoft SQL Server
* **IDE:** Microsoft Visual Studio
* **Architecture:** Windows desktop application with separate business logic and data-access components

## Project Structure

```text
RecruitmentPortal
│
├── BusinessLogic
├── DataManager
├── Properties
├── Reg_Photo
├── Reports
├── App.config
├── Frm*.cs
├── Frm*.Designer.cs
├── MDIParentAdmin.cs
├── MDIParentCandidate.cs
├── Program.cs
└── RecruitmentPortal.csproj
```

## Application Workflow

```text
Candidate
   ↓
Registration / Login
   ↓
View Jobs
   ↓
View Job Details
   ↓
Apply for Job
   ↓
Application Management
```

```text
Admin
   ↓
Admin Login
   ↓
Manage Job Posts
   ↓
View Candidates
   ↓
View Applications
   ↓
Manage Recruitment Data
```

## Database

The application uses **Microsoft SQL Server** to store recruitment-related information such as candidate registrations, job postings, and applications.

A database script can be provided separately for creating the required database structure.

## Project Purpose

This project demonstrates the development of a **desktop-based recruitment management system**, including Windows Forms UI development, database connectivity, form-to-form navigation, business logic implementation, and recruitment workflow management.

## Note

This project is intended for **learning, demonstration, and portfolio purposes**. Database configuration and local environment settings may need to be updated before running the application on another machine.

## Author

**Anish K**
