# Project Proposal: Infinity University Management System

## 1. Project Overview

The **Infinity University Management System (IUniMS)** is a web-based university administration prototype. It brings core academic and administrative activities into one portal and provides separate workspaces for administrators, teachers, and students. Each role sees tools suited to its responsibilities, while shared records connect processes such as course registration, attendance, assessments, results, fees, and notices.

The prototype is designed to demonstrate how a university can coordinate routine operations through a central system instead of maintaining disconnected records and communication channels.

## 2. Problem Statement

Universities handle a large amount of related information, including student records, course offerings, class schedules, attendance, examination results, fees, and announcements. When these records are maintained separately, staff and students may have difficulty finding current information, tracking approvals, and coordinating academic tasks. A role-based management portal can make these workflows easier to follow and provide users with a clearer view of their responsibilities and records.

## 3. Project Objectives

- Provide a common portal for important academic and administrative workflows.
- Organize access around administrator, teacher, and student responsibilities.
- Demonstrate the flow from course registration requests to administrative review.
- Support course resources, attendance, assessments, grade review, and student results.
- Make schedules, notices, financial records, and student information easier to view.
- Preserve prototype changes in browser storage so demonstration data remains available after a page refresh.

## 4. Role-Based Features

### 4.1 Administrator Workspace

The administrator oversees the university's academic setup, people, and institutional records.

| Feature area | Description |
|---|---|
| **Dashboard and analytics** | Shows institutional summaries and gives administrators a starting point for monitoring university activity. Reports cover areas such as enrollment, attendance, results, and finance, with available data export options. |
| **User and role management** | Supports administration of user accounts and account status. The prototype provides separate role access for Administrator, Teacher, and Student. |
| **Students and admissions** | Provides student records and admission application workflows. Administrators can review applications and maintain student program and enrollment information. |
| **Academic structure** | Manages faculties, departments, programs, courses, credits, prerequisites, academic years, semesters, and class sections. These records provide the structure used throughout the academic workflows. |
| **Scheduling** | Allows administrators to maintain class routines and examination schedules, including assigned teachers, rooms, and time slots. Scheduling validation helps identify conflicts. |
| **Attendance oversight** | Provides views of attendance records across courses and students for institutional monitoring. Teachers enter attendance in their course workspace. |
| **Fees and payments** | Maintains fee accounts, charges, payment records, receipts, outstanding balances, and payment status for students. |
| **Examinations and results** | Supports examination setup and result management. Teacher grade submissions can be reviewed by the administrator before results are approved. |
| **Course registration review** | Displays student registration requests and allows administrators to approve, reject, or reopen a request. Students can see the resulting status in their portal. |
| **Notices and system settings** | Supports university notices and announcements, along with configuration of system settings and institutional information. |

### 4.2 Teacher Workspace

The teacher workspace focuses on assigned courses, classroom activity, and student assessment.

| Feature area | Description |
|---|---|
| **Profile and dashboard** | Shows the teacher's assigned courses, classes, and notices. Teachers can update contact and profile information. |
| **Course and student lists** | Lets teachers view the courses assigned to them and the students associated with those courses. Student lists can be downloaded for classroom use. |
| **Learning resources** | Allows teachers to upload course materials, syllabus files, and other resources for students to access. Course announcements can be shared with the relevant students. |
| **Attendance** | Records attendance by course and date. Teachers can review attendance summaries and identify students whose attendance is below the configured threshold. |
| **Assessments and grading** | Supports creation of assignments, quizzes, and exams, entry of student marks, and submission of grades for administrator review. The teacher can download a mark sheet and see the approval status of grade submissions. |
| **Assignment review** | Displays online assignment responses and attached files submitted by students for the selected assessment. |
| **Communication** | Lets teachers send course messages and notices, view student queries, and reply to those queries. |
| **Reports** | Provides course-level performance and attendance summaries for the teacher's assigned classes. |

### 4.3 Student Workspace

The student workspace gives students a personal view of their academic progress, campus information, and university interactions.

| Feature area | Description |
|---|---|
| **Profile and dashboard** | Displays the student's identifying academic information, course count, attendance summary, GPA/CGPA, outstanding fees, notices, schedule, and pending assignment tasks. Students can update their contact details. |
| **Course registration** | Shows active courses available to the student's program and allows semester registration requests. Students can review whether each request is pending, approved, or rejected. |
| **Learning resources and assignments** | Provides access to course files shared by teachers. Students can submit assignment text responses and optional file attachments before the due date. |
| **Attendance and routine** | Shows course attendance totals and dated attendance records, along with scheduled classes and examinations for the student's courses. |
| **Results** | Displays published marks, grades, grade points, GPA, and CGPA. Students can download a result sheet for their records. |
| **Fees and payments** | Shows fee charges, billed and paid totals, outstanding balances, and payment history. Fee statements and payment receipt records can be downloaded. |
| **Communication** | Displays relevant notices, course messages, and conversation threads. Students can send queries to a course teacher or requests to administration and view teacher replies. |

## 5. Typical Workflow

1. An administrator creates the academic structure, course offerings, schedules, and student records.
2. A student submits a course registration request for a semester.
3. An administrator reviews the request and updates its status; the student sees the decision in the portal.
4. A teacher shares learning materials, records attendance, and creates assessments for assigned courses.
5. Students access resources and submit assignments; teachers review submissions and enter grades.
6. Teachers submit grades for administrator approval. Approved academic results become available to students.
7. Students view their attendance, results, schedules, fee accounts, notices, and communication history.

## 6. Technology and Data Handling

The application is built with **Angular and TypeScript**. It uses **PrimeNG** for interface components and a responsive dashboard layout for the role-based workspaces. Typed data models and application services organize the academic records and workflow operations. Seed data supports demonstrations, while browser storage persists changes on the current browser and device.

## 7. Scope and Limitations

This project is a functional prototype for demonstration and academic project evaluation. Authentication uses demonstration credentials, and application data is stored in the browser rather than in a university server database. Uploaded materials and assignment attachments are also stored in browser storage. Payments are represented as records; the prototype does not connect to a payment provider. A production system would need secure server-side authentication, a central database, permission enforcement, backup and recovery, privacy controls, and integrations with institutional systems.

## 8. Expected Outcome

The expected outcome is a unified, role-based university portal that demonstrates how administrators, teachers, and students can participate in connected academic and administrative workflows. It provides a foundation for future development into a secure system backed by institutional infrastructure.

---

## Final Section: Demonstration Accounts

The following accounts are for prototype demonstration:

| Role | Username | Password |
|---|---|---|
| Administrator | `Administrator` | `Admin@123` |
| Teacher | `Teacher1` | `Teacher@123` |
| Student | `Student1` | `Student@123` |
