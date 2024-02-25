# Origination BPM

This repository contains Process, Decision and Case management assets required for **Origination** App

## Process Management
### Application Submission : 
Process triggered upon submitting application in origination app to do the following:
- Create user task for manual review if application status is *Under Review*.
- Update all applicants in **Party MS**, **Transact** and **DBXDB**.
- Create accounts  in **Transact** for all the products selected in the application.
- Notify all the applicants based on application status.

### Funding Request: 
Process triggered upon submitting funding request in origination app to do the following:
- Execute funding instruction for all the accounts user selected.

## Decision Management
### Applicant Status:
DMN to calculate individual applicant's status based on IDV and Selfie scores.
### Application Status:
DMN to calculate overall application status based on each applicant's status.