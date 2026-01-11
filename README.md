# Employee-Doctor-Dashboard

This assignment comprises a Health Care Portal web application that is responsive and constructed with HTML, CSS, and pure JavaScript. It mimics a system that has different interfaces for Patients and Doctors with the following characteristics:

Role-Based Login: It is a separate login process for patients and doctors (one must have a Doctor ID).

Patient Dashboard: It reveals personal information alongside upcoming appointments (with a toggle for completion), visit history, prescribed therapies, doctor's notes, a personal health journal (using localStorage), and a health trends chart (using Chart.js).

Doctor Dashboard: It reveals the doctor’s information, a list of patients assigned to the doctor that can be searched and sorted, a schedule view, and a detailed patient view with tabbed sections (History, Visits, Exercises, Notes, Log Visit) where doctors can provide comments/recommendations, and log new visits for selected patients.

Modern UI: It supports light/dark theme, has responsive design for various screen sizes, uses skeleton loaders to show that data is loading, comprises interactive components (buttons, cards, forms, modals, tooltips), and visual effects such as glassmorphism and neon glows.

Client-Side Logic: The entire data (doctors, patients, visits, etc.) is pretended in the JavaScript file, and the application logic including authentication, data rendering, and interactions is done on client-side.
