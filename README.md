# API-Testing-Postman
# API Testing Portfolio: Conduit (RealWorld App)

This project showcases a comprehensive approach to API testing for the Conduit web application, a Medium.com clone. The entire testing process, from initial analysis to test execution and light automation, was performed using Postman.

## Objective
The primary goal of this project is to demonstrate a systematic and professional QA process for testing a REST API. This includes:
* Analyzing API behavior based on network traffic.
* Creating a structured test collection in Postman.
* Writing automated checks for key functionalities.
* Managing test data and authentication flows.

---

## Technologies and Tools
* **Postman:** For creating and executing API requests and automated tests.
* **Git & GitHub:** For version control and project documentation.
* **Google Sheets:** For initial test analysis and documentation of API endpoints.

---

## Scope of Testing & Action Plan

This project covers the full lifecycle of a user and their content on the platform. The test suite is structured to cover the following end-to-end scenarios:

#### 1. User Management
    * **Registration:** Create a new user account.
    * **Authentication:** Log in to receive an authorization token.
    * **Get Profile:** Retrieve user profile information.

#### 2. Article Management (as an authenticated user)
    * **Create Article:** Post a new article.
    * **Update Article:** Edit an existing article.
    * **Delete Article:** Remove an article.

This action plan will be implemented by creating a structured Postman collection where the authentication token from the login process is automatically captured and used in subsequent authenticated requests, demonstrating a **light automation** workflow.
