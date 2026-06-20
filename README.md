CI/CD Final Project
Overview

This project demonstrates the implementation of a Continuous Integration and Continuous Deployment (CI/CD) pipeline using GitHub Actions. The pipeline automates code testing, building, and deployment processes to improve software quality and delivery speed.

Features
Automated testing using GitHub Actions
Continuous Integration for every code commit
Automated build process
Continuous Deployment workflow
Version control with GitHub
Technologies Used
GitHub
GitHub Actions
Python
Flask
Docker
Project Structure
.
├── .github/
│   └── workflows/
│       └── ci-build.yaml
├── service/
│   ├── routes.py
│   ├── models.py
│   └── common/
├── tests/
├── Dockerfile
├── requirements.txt
└── README.md
CI/CD Pipeline

The pipeline performs the following tasks:

Checkout source code
Install dependencies
Run unit tests
Perform code quality checks
Build application
Deploy application
Running the Application
Clone the Repository
git clone <repository-url>
cd <repository-name>
Install Dependencies
pip install -r requirements.txt
Run the Application
python app.py
Running Tests
nosetests
Author

Created as part of the DevOps and Software Engineering Final Project.
