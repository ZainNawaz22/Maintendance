# Maintendance
Maintendance aims to simplify and enhance the administrative processes related to employee attendance and leave management, fostering a more organized and efficient workplace environment.
Maintendance is a robust desktop application designed to streamline and automate the management of employee attendance and leave processes within an organization. Built using the Qt framework in C++, Maintendance offers a user-friendly interface tailored for different user roles, ensuring efficient handling of attendance records, leave applications, and administrative approvals.

Key Features
Role-Based Access Control:

Director: Oversees the entire attendance and leave management system, with capabilities to approve or reject leave applications, and view comprehensive reports.
Supervisor: Manages attendance records for employees and guards, approves or rejects leave requests, and monitors pending applications.
Guard: Marks daily attendance, ensuring accurate logging of presence, absence, or leave statuses.
General Employee: Views personal attendance records, applies for leaves, and monitors leave balances.
User Authentication:

Secure login system with rounded and aesthetically pleasing input fields for usernames and passwords.
Different login interfaces for Directors, Supervisors, Guards, and Employees to ensure appropriate access levels.
Attendance Management:

Mark Attendance: Guards can mark their attendance daily, with the system preventing duplicate entries for the same day.
View Attendance: Employees can view their personal attendance logs, while Supervisors and Directors can access attendance records of all employees or specific individuals.
Attendance Percentages: Real-time calculation and display of monthly and weekly attendance percentages for employees, aiding in performance assessments.
Leave Management:

Apply for Leave: Employees can submit leave applications specifying the type (Casual, Earned, Official, Unpaid), duration, and reason.
Approve/Reject Leave: Supervisors and Directors have the authority to approve or reject leave requests, with the system updating attendance logs and leave balances accordingly.
Pending Applications: Supervisors and Directors can view and manage pending leave applications, ensuring timely processing and updates.
Leave Balance Tracking:

Real-time tracking of leave balances for different leave types, allowing employees to monitor their available leaves.
Structured storage and retrieval of leave balances, ensuring accuracy and easy access for users.
Dynamic UI with Qt:

Intuitive and responsive user interfaces for all user roles, built using Qt’s QWidget framework.
Enhanced visual elements such as rounded input fields, dynamic tables, and informative message boxes for better user experience.
Data Management:

Structured file-based storage for attendance logs and leave applications, organized systematically per employee and role.
Efficient reading and writing mechanisms to handle large volumes of attendance and leave data without compromising performance.
Error Handling and Validation:

Comprehensive checks to prevent duplicate attendance entries and ensure valid leave applications.
User-friendly error messages guiding users to correct their inputs and actions.
Technical Specifications
Programming Language: C++
Framework: Qt 6.8.0
IDE: Visual Studio Code with integrated support for Qt development
Build System: MinGW 64-bit
Version Control: Git, with .gitignore configured to exclude unnecessary files and directories.
Project Structure
Core Components
User Classes:

Employee: Base class for general employees, managing personal attendance and leave records.
Guard: Derived from Employee, with additional functionalities to mark daily attendance.
Supervisor: Manages a team of employees and guards, handles leave approvals, and oversees attendance records.
Director: Senior role with comprehensive oversight of all attendance and leave activities, including final approval powers.
UI Components:

Login Interfaces: Separate .ui files for each role, ensuring tailored user experiences.
Attendance and Leave Dialogs: Interactive dialogs for viewing and managing attendance and leave data.
Tables and Forms: Dynamic tables for displaying records, with functionalities to sort, filter, and update entries.
Data Handling:

Attendance Logs: .txt files storing daily attendance entries, structured per employee.
Leave Applications: Organized storage of leave requests, statuses, and balances, facilitating easy access and management.
Usage Workflow
Logging In:

Users select their role and enter credentials on the login page.
Upon successful authentication, users are redirected to their respective dashboards.
Employees:

View personal attendance records and leave balances.
Apply for various types of leaves with necessary details.
Guards:

Mark daily attendance, ensuring no duplicate entries for the same day.
View personal attendance logs and leave statuses.
Supervisors:

Access and manage attendance records of assigned employees and guards.
Approve or reject leave applications, updating relevant logs and balances.
Monitor pending leave requests and overall team attendance statistics.
Directors:

Oversee all attendance and leave activities across the organization.
Final authority on approving or rejecting leave applications.
Generate comprehensive reports and summaries on attendance metrics and leave statistics.
Error Handling and Stability
Validation Checks: Ensures that all user inputs are validated to prevent inconsistencies and errors, such as duplicate attendance entries or invalid leave requests.
Memory Management: Carefully manages dynamic memory allocations to prevent leaks and crashes, with proper cleanup mechanisms in destructors.
User Feedback: Provides informative messages and warnings using QMessageBox to guide users in case of errors or invalid actions.
Future Enhancements
Comprehensive Reporting: Implement detailed reporting features for Directors and Supervisors to analyze attendance trends and leave patterns.
Notification System: Introduce email or in-app notifications for leave approvals, rejections, and reminders.
Integration with Calendars: Sync attendance and leave schedules with calendar applications for better planning.
Role Expansion: Add more roles with specific permissions and functionalities to accommodate varied organizational structures.
Maintendance aims to simplify and enhance the administrative processes related to employee attendance and leave management, fostering a more organized and efficient workplace environment.
