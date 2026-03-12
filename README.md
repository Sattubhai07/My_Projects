# My_Projects
this Repository Contains Production Grade Projects I Have Build

1. Library Seat Booking Website(Fully online)

Title: APJ Library Management System - Automating Operations & Revenue Tracking

The Problem:
The library owner was managing 100+ seats using manual registers and Excel sheets. This led to several operational issues:

* Seat Conflicts: Double booking of seats due to human error.
* Revenue Leakage: Difficulty in tracking payments, renewals, and expired memberships.
* Shift Management: Manually managing Day and Night shift students was chaotic.
* No Student Portal: Students had to physically visit or call to check availability.

The Solution:
I developed a production-grade Full-Stack Web Application to digitize the entire process.

* Automated Seat Booking: A visual, interactive seat map (like movie ticketing) allowing students to book specific seats in real-time.
* Dynamic Shift Logic: Smart algorithm to handle Day Shift (S1-S80) and Night Shift (S61-S80) overlapping rules automatically.
* Integrated Payments: Seamless Razorpay integration with automatic receipt generation and database updates.
* Auto-Expiry System: Background jobs (Cron) that automatically free up seats when a membership expires and notify students via Email/SMS.

The Result (Impact):

* 100% Automation: The client no longer manually tracks seats or payments.
* Zero Conflicts: The system prevents double booking instantly.
* Increased Revenue: Automated renewal reminders (5 days prior) improved retention rates.
* Better User Experience: Students can now view seat availability and book from home.

  
Tech Stack: React.js, Node.js (Express), MySQL, Nginx, Razorpay API, JWT Auth.

