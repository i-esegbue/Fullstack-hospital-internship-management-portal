# Hospital Internship Management Portal (Full-Stack Web Application)

A secure, role-based full-stack web application that enables students to browse and apply for hospital internships while allowing employers and administrators to review and manage applications through dedicated dashboards.

## Key Features

* **Role-Based Access Control (RBAC):** Separates user permissions and dashboards across three distinct user roles—Students, Employers, and Administrators.
* **Secure Authentication & Session Management:** Protects user accounts and restricted routes with custom login, profile management, and session logout workflows.
* **Student Application Portal:** Allows students to explore available clinical and hospital job roles, manage their profiles, and submit internship applications.
* **Employer & Admin Dashboards:** Enables hospital recruiters and system administrators to review incoming applications, manage listings, and download applicant documents securely.
* **Responsive Mobile-First UI:** Built with **Bootstrap 5**, custom CSS, and JavaScript to deliver a clean, responsive layout across desktop, tablet, and mobile screens.

## Tech Stack

* **Front-End:** HTML5, CSS3, Bootstrap 5, JavaScript
* **Back-End:** PHP
* **Architecture:** Multi-role server-side rendered web application with session-based security

## Project Structure

* `/admin` — Administrative dashboard and system management views
* `/employer` — Employer portal for reviewing and managing internship applications
* `/student` — Student interface for browsing roles and tracking applications
* `/includes` — Shared server-side PHP configuration, authentication, and helper scripts
* `/css`, `/js`, `/images` — Front-end stylesheets, client-side scripts, and static visual assets

## Local Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/i-esegbue/Fullstack-hospital-internship-management-portal.git
   ```
2. Move the project folder into your local PHP server directory (e.g., `htdocs` for XAMPP or `www` for WAMP).
3. Start your Apache and MySQL services in your local server control panel.
4. Open your browser and navigate to `http://localhost/secure-web-application/index.php`.
