# FlightBookingAutomation
Automated end-to-end testing of a flight booking web application using Selenium and TestNG. Validates flight search, booking, and confirmation processes with a Page Object Model framework, data-driven testing, and detailed reporting for improved test efficiency and reliability.

✈️ Flight Booking Automation Framework

A robust Test Automation Framework built for TripEase Flight Booking App, featuring Selenium WebDriver, TestNG, RestAssured, and Maven — designed to validate both UI and API flows efficiently.

🧩 Test Modules
🔹 UI Automation

Validates the end-to-end flight booking flow using Selenium and TestNG.

Flow Covered:

Open TripEase (mock HTML or live site)

Enter From and To cities

Select Departure Date

Search available flights

Choose a flight and proceed to booking

Validate booking confirmation
🔹 API Automation

Validates REST API endpoints for backend booking and user creation.

Endpoints Tested:

Method	Endpoint	Description
POST	/users	Create a new user
GET	/bookings	Fetch booking list
POST	/bookings	Create a new booking
DELETE	/bookings/:id	Cancel booking

Framework:
Built using RestAssured and integrated with TestNG for assertions and reporting.

🧠 Design Principles

Page Object Model (POM) for scalability

Thread-safe WebDriver using ThreadLocal

Parameterization with TestNG @Parameters

Headless/Non-headless Modes

Auto Driver Management with WebDriverManager

Assertions via TestNG

Custom waits and retry mechanisms for stability

🔍 Reports

TestNG HTML Reports:
Generated in target/surefire-reports/ after every test run.

JUnit XML Reports:
Found under target/surefire-reports/junitreports/.

Console Logging:
SLF4J integrated for cleaner output.

🔒 Best Practices

Implicit waits kept minimal; explicit waits used for dynamic elements

Graceful teardown with safe quit

Overlays and cookie popups handled automatically

Tests skip safely if required parameters are missing

Works offline via local mock HTML (tripease.html)

📄 License

MIT License © 2025 — Flight Booking Automation Framework
