KLU STUDENT MANAGEMENT PORTAL
=============================
Technology: HTML + CSS + JavaScript + localStorage

RUN:
1. Extract the folder.
2. Open index.html in Chrome/Edge, or use VS Code Live Server.
3. Demo logins:
   Admin:   admin / admin123
   Faculty: FAC1001 / faculty123
   Student: 2500030599 / student123

IMPORTANT FLOW:
Admin -> New Student Allocation -> creates student + login credentials.
Faculty -> My Students -> immediately sees the new student.
Faculty -> Enter Marks / Attendance -> saves data for that student.
Student -> logs in with allocated credentials -> sees profile, marks and attendance.

FOLDERS:
admin/   Admin pages and features
faculty/ Faculty pages and features
student/ Student pages and features
css/     Shared design
js/      Shared JavaScript/data logic

This is a browser-only academic/demo project. localStorage is used instead of a server database.
