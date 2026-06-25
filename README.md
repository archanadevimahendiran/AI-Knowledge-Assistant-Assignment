# AI Knowledge Assistant – QA Assessment

## Overview

This repository contains my submission for the AI Knowledge Assistant QA assessment.

The objective of the assessment was to evaluate the application from a manual QA perspective by identifying high-risk scenarios, designing a regression suite, validating access controls, and documenting defects.


## Scope

The assessment focused on:

- Risk-based testing
- Role-based access control
- Region-based access control
- Document lifecycle validation
- Citation validation
- Prompt injection testing
- Unsupported query handling


## Deliverables

- QA Assessment Report (PDF)
- Defect reports with supporting screenshots
- Golden Question Regression Suite
- Risk-based testing approach



## Defects Identified

- Retired document returned instead of approved document
- Prompt injection exposed a Draft document
- In Review document returned to an unauthorized user
- Citation validation issue (if reproducible)



## Test Approach

The application was tested manually using a risk-based approach, prioritizing business-critical areas such as document lifecycle validation, access control, citation accuracy, and prompt injection.



## Repository Structure

```text
Documentation/
Defects/
TestData/
Assets/
```



## Tools Used

- Google Chrome
- Microsoft Word
- GitHub

---

Prepared by **Archana**
