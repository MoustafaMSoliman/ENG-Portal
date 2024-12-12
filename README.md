# ERP System for Academic Institution (DDD Project)

## Overview
This is a Domain-Driven Design (DDD) ERP system developed using .NET Core, specifically tailored for an academic institution. The system serves the needs of different users, including administrators, academic staff, students, and employees in various departments.

## Features

### User Roles
- **Administrators**:
  - Have the highest level of control.
  - Can promote employees to managers.
  - Oversee the entire system operations.
  
- **Managers**:
  - Manage employee activities.
  - Monitor and facilitate tasks related to exams, departmental work, and student activities.
  
- **Academic Staff**:
  - Create and manage exams.
  - Record and analyze student performance.
  
- **Students**:
  - Access exams and results.
  - Participate in course-related activities.
  
- **Employees**:
  - Support academic and operational activities.
  - Collaborate with managers and staff in their assigned departments.

### Core Modules
1. **User Management**:
   - Role-based access control.
   - Functionality for administrators to assign and manage roles.

2. **Departmental Structure**:
   - Each department has a defined hierarchy and assigned users.
   - Supports custom workflows per department.

3. **Exams Management**:
   - Creation and scheduling of exams.
   - Automated grading and result generation.

4. **Task Management**:
   - Assigning tasks to employees.
   - Tracking progress and performance.

5. **Reports and Analytics**:
   - Generate insights on student performance and departmental activities.

### Technologies Used
- **Backend**: .NET Core (C#)
- **Frontend**: ASP.NET Core MVC or Blazor (Optional)
- **Database**: SQL Server
- **Architecture**: Domain-Driven Design with layered architecture (Domain, Application, Infrastructure, Presentation).

## Installation

### Prerequisites
- .NET Core SDK
- SQL Server
- Git

### Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo/erp-ddd-academic.git
   cd erp-ddd-academic
