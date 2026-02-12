Project Overview:
This repository contains the Week 6 QA Internship Project, including automation scripts, manual testing documents, and CI/CD workflow.

Contents:

.github : GitHub Actions workflow for CI/CD automation

automation : Python Selenium scripts

manual-testing : Test Plan, Test Cases, Bug Reports, Compatibility, Performance, Security Reports

assets : Supporting files

report.html : PyTest HTML report

CI/CD Pipeline:

Workflow is defined in .github/workflows/qa-workflow.yml

Trigger: Push on the main branch

Steps: Checkout code, Setup Python 3.10, Install dependencies, Run PyTest automation scripts, Generate report.html

How to Run Locally:

Clone the repository: git clone https://github.com/EliteZain657/SQA_INTERNSHIP_WEEK-6.git

Navigate to project folder: cd SQA_INTERNSHIP_WEEK-6

Setup Python environment (optional):

python -m venv venv

venv\Scripts\activate (Windows)

pip install -r automation/requirements.txt

Run tests: pytest automation/ --html=report.html

Notes:

Manual QA documents are in manual-testing folder

CI/CD pipeline runs automatically through GitHub Actions

Test report is generated as report.html
