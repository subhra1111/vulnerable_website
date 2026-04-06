# vulnerable_website
Vulnerable Web App
This is an educational frontend project demonstrating common web vulnerabilities from the OWASP Top 10, such as SQL Injection, XSS, and Broken Access Control.

Features
Home Page: Introduction to the app and vulnerabilities (index.html).

Login: Vulnerable authentication form (login.html).

Dashboard: Protected user area with links to admin and comments (dashboard.html).

Comments: Section with XSS payload injection via textarea and iframe (comments.html).

Admin Panel: Exposes cleartext user database dump with no auth checks (admin.html).

Files
File	Description
index.html	Landing page 
login.html	Login form 
dashboard.html	User dashboard 
admin.html	Admin database viewer 
comments.html	Comments with XSS demo 
style.css	Shared styles 
app.js	Client-side logic and API fetches 
Setup
Serve files with a local HTTP server (e.g., python -m http.server or Live Server extension) since fetch API requires HTTPS/HTTP.

Backend API endpoints (/api/login, /api/user, /api/comments, /api/admin/users) are referenced but not included—implement separately for full functionality.

Note: Created by Subhranil Bar for ethical hacking learnin
