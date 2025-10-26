🛡️ E2E API Testing Project: Courses Application

🌐 Project Documentation: Postman E2E Testing Project

📖 Description

This repository demonstrates the practical application of End-to-End (E2E) API testing using Postman, Newman, and Jenkins, as learned from a complete Postman course.

The project simulates testing a Courses API with CRUD operations (Create, Read, Update, Delete) while applying best practices in test design, automation, and CI/CD.

Key Project Deliverables

Comprehensive API Test Collection: Covers all main API endpoints (login, post a course, get course, update course, delete course).

Automated Test Execution: Implemented via Newman CLI and generated HTML reports using htmlextra.

CI/CD Pipeline: Configured Jenkins to run E2E tests automatically, including scheduling repeated runs.

🚀 Key QA Skills & Features

🔬 API Functional & Negative Testing: Verified core functionality and tested edge cases with invalid or missing data.

📝 Assertions & Response Validation: Checked status codes, response times, and response payloads for correctness.

📊 Reporting & Documentation: Generated HTML reports and tracked results using spreadsheets for detailed traceability.

🔄 CI/CD Implementation: Automated test runs using Jenkins for continuous integration.

📌 Environment & Global Variables: Managed environment variables to switch between local and mock servers efficiently.

🛡️ Basic Security Checks: Tested authentication endpoints and secured paths for protected resources.

🛠️ Technologies Used

Postman — API testing and collection management.

Newman & Newman htmlextra — CLI automation and HTML reporting.

Jenkins — CI/CD setup to run E2E tests automatically.

Insomnia — Optional API testing tool for comparison and validation.

Google Sheets / Excel — Test case and bug tracking.

Node.js / JSON Server — Local fake server for testing.

📌 Project Status
Task	Status	Notes
API Test Collection creation	✅ Completed	All endpoints covered
Test Assertions & Scripts	✅ Completed	Status codes, payloads, and response time
Automated Execution (Newman)	✅ Completed	CLI & HTML report generated
CI/CD Setup (Jenkins)	⚡ In Progress	Scheduled runs implemented
Test Documentation	⚡ In Progress	Test cases & results tracked in spreadsheets
Additional Security & Performance Testing	❌ Planned	Future improvements
📷 Preview






📌 Future Scope & Improvements

SQL Integration: Validate backend database after API calls.

UI Testing: Extend to Cypress / Playwright for UI test automation.

Advanced CI/CD: Integrate Docker or GitHub Actions for cross-platform automation.

Performance Testing: Add stress/load tests using JMeter or Locust.
