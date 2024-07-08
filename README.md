

# Software Testing Project for Author Role

This project involves automated testing of a web page for the author role using JUnit and Selenium WebDriver. The tests cover various functionalities such as submitting papers, editing submissions, uploading camera-ready forms, updating payment details, and adding co-authors.

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Running the Tests](#running-the-tests)
- [Test Cases](#test-cases)
  - [CMS_09_SubmitPaper](#cms_09_submitpaper)
  - [CMS_10_EditSubmission](#cms_10_editsubmission)
  - [CMS_11_UploadCameraReadyForm](#cms_11_uploadcamerareadyform)
  - [CMS_12_UpdatePaymentDetails](#cms_12_updatepaymentdetails)
  - [CMS_13_AddCoAuthors](#cms_13_addcoauthors)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project is designed to test the functionalities of a web application specifically for users in the author role. The tests are automated using JUnit and Selenium WebDriver to ensure the web application performs as expected.

## Technologies Used

- Java
- JUnit
- Selenium WebDriver
- ChromeDriver

## Setup Instructions

1. **Clone the repository:**
    ```sh
    git clone https://github.com/your-username/your-repository.git
    cd your-repository
    ```

2. **Install dependencies:**
    - Ensure you have Java and Maven installed on your system.
    - Install the ChromeDriver and place it in an accessible location.
    - Update the `chromedriver` path in the `TestCase3_287471` class.

3. **Update WebDriver path:**
    In the `TestCase3_287471` class, update the path to the ChromeDriver executable:
    ```java
    System.setProperty("webdriver.chrome.driver", "path/to/your/chromedriver.exe");
    ```

4. **Set up the test user credentials and files:**
    - Update the login credentials and file paths in the `login` method and relevant test cases as per your test environment.

## Running the Tests

1. **Navigate to the project directory:**
    ```sh
    cd your-project-directory
    ```

2. **Run the tests using Maven:**
    ```sh
    mvn test
    ```

## Test Cases

### CMS_09_SubmitPaper

This test case automates the process of submitting a new paper.

### CMS_10_EditSubmission

This test case automates editing an existing paper submission and verifying the changes.

### CMS_11_UploadCameraReadyForm

This test case automates uploading camera-ready documents and verifying the status update by an admin.

### CMS_12_UpdatePaymentDetails

This test case automates updating payment details and uploading proof of payment.

### CMS_13_AddCoAuthors

This test case automates adding co-authors to a paper submission.
