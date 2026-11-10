# Campus — Student Information Portal

A frontend-only portal built with HTML, custom CSS, JavaScript, and locally bundled Bootstrap 5.3.3 CSS. No backend, build process, or package installation is required.

## Run locally
Open `index.html` from the extracted source folder in a modern browser. For consistent browser storage behavior, serve the folder with any static web server, such as `python -m http.server 8000`, and visit http://localhost:8000.

## Demo sign-in
Email: admin@campus.edu
Password: Campus2026!

Alternatively, select “Explore demo portal”. Credentials are intentionally public for demonstration. This is not secure authentication and does not restrict access to records.

## Features
- Responsive login and faculty dashboard
- Sample student directory with search, program/year/status filters, name sorting, and pagination
- Add students, view profiles, and edit student information
- Required fields and duplicate ID/email validation
- Browser-local record persistence using localStorage; no data is sent to a server
- Academic program enrollment summaries
- Export current filtered results to CSV
- Mobile navigation and native accessible dialogs

Only use fictional data in this demonstration. Signing out returns to the login view without deleting browser-local records. Changes are not synchronized between browsers or devices. Clear the `campus.students.v1` localStorage key to restore the sample dataset on reload. A production portal requires server-side authentication, authorization, validation, and protected data storage.

## Files
- index.html: page structure and dialogs
- styles.css: custom design and responsive layouts
- app.js: frontend interactions and sample records
- assets/bootstrap.min.css: Bootstrap 5.3.3 (MIT), https://getbootstrap.com/
