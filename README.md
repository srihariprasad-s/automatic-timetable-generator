# automatic-timetable-generator
An Intelligent, Rule-Based Timetable Generation System with Collision Detection Built using PHP, MySQL (phpMyAdmin), and hosted locally via WAMP Server.
📌 Project Description
This project streamlines the creation and management of academic timetables for institutions by providing the ability to:

Assign staff based on department.

Create and manage classes, batches, and courses independently.

Generate template-based timetable structures to avoid repetitive formatting.

Detect and prevent staff schedule collisions using a rule-based engine.

Allow confirmation of assignments to prevent re-randomization on page reload.

Export and download the generated timetables for offline usage.

It is ideal for schools, colleges, and universities looking for a semi-automated but controlled method of managing complex teaching schedules.

🧩 Key Features
🧑‍🏫 Staff Assignment by Department
Staff are grouped and selected based on their department.

Prevents cross-department conflicts and maintains a clean hierarchy.

🏫 Batch & Class Management
Easily create classes using batch-wise logic (e.g., 2023–2027, Year 1–4).

Manage course assignments to specific classes and batches.

📄 Template-Based Timetable Format
Define reusable templates with period timings, breaks, and rules.

Speeds up future schedule creation by avoiding redundant setup steps.

🧠 Rule-Based Collision Detection
Checks both:


Prevents a staff member from being double-booked across overlapping sessions.

🔁 Confirm/Change Assignment Flow
✅ Confirm Assignment: Locks the current timetable set and saves it to the database.

🔁 Change Assignment: Triggers regeneration of timetable suggestions.

Prevents random changes on reload unless the user explicitly opts for it.

⬇️ Export & Download Option
Allows users to download generated timetables as PDF or Excel for easy distribution.

🛠️ Tech Stack
Component	Technology
Backend	PHP (Procedural or OOP)
Database	MySQL (phpMyAdmin)
Local Server	WAMP Server
Frontend	HTML, CSS, JavaScript
