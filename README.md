# API Testing Portfolio: Conduit (RealWorld App)

This project showcases a comprehensive approach to API testing for the Conduit web application, a Medium.com clone. The entire testing process, from initial analysis to test execution and automation, was performed using Postman.

This repository contains the full Postman collection with **9 requests** and a total of **18 automated tests** covering core application functionalities.

## Objective
The primary goal of this project is to demonstrate a systematic and professional QA process for testing a REST API. This includes:
* Analyzing API behavior based on network traffic.
* Creating a structured test collection in Postman with automated tests.
* Writing various assertions to check not only status codes but also response body content and structure.
* Managing test data and authentication flows using collection variables.

---

## Technologies and Tools
* **Postman:** For creating and executing API requests and automated tests.
* **Git & GitHub:** For version control and project documentation.
* **Google Sheets:** For initial test analysis and documentation of API endpoints.

---

## Scope of Testing

This project covers the full lifecycle of a user and their content on the platform. The test suite is structured to cover the following end-to-end scenarios:

#### 1. User Management
    * **Registration:** Create a new user account.
    * **Authentication:** Log in to receive an authorization token.
    * **Get Profile:** Retrieve user profile information.
    * **Follow/Unfollow User:** Test the social interaction functionalities.

#### 2. Article & Content Management
    * **Create Article:** Post a new article as an authenticated user.
    * **Update Article:** Edit an existing article.
    * **Delete Article:** Remove an article.
    * **Add/Delete Comments:** Test the comment functionalities on articles.

---

## Project Assets

* **Test Analysis & Documentation:**
    * [View the detailed API analysis in Google Sheets](https://docs.google.com/spreadsheets/d/1XVc5XA-C58SMYXYMnmrd8rCwSR4N4sc_s1blDAsoIxw/edit?usp=sharing)

* **Postman Collection:**
    * The complete Postman collection with all requests and automated tests can be found in this repository. You can import it directly into Postman.
    * [Conduit API Testing.postman_collection.json](./Conduit%20API%20Testing.postman_collection.json)
