# ParaBank Online Banking – Manual Testing Project

## Project Overview

This project demonstrates manual software testing of the **ParaBank Online Banking** web application. The objective was to validate core banking functionalities, identify defects, and document test execution results using standard QA practices.

**Application Under Test:** [ParaBank Online Banking](https://parabank.parasoft.com/parabank/index.htm)

**Testing Type:** Manual Functional Testing

**Application Domain:** Banking

**Tools Used:** Google Chrome, Microsoft Excel, Google Drive, GitHub

## Testing Objectives

- Verify core banking functionalities.
- Validate positive and negative test scenarios.
- Check form validations and error handling.
- Verify account transactions and fund transfers.
- Test login, logout, and session management.
- Identify, document, and retest application defects.

## Modules Tested

1. User Registration
2. Login and Logout
3. Accounts Overview and Account Details
4. Fund Transfers
5. Bill Payments
6. Transaction Search
7. Profile Updates
8. Navigation and Session Management

## Test Execution Summary

| Metric | Result |
|---|---|
| Total Test Cases | 52 |
| Executed | 52 |
| Passed | 41 |
| Failed | 10 |
| Not Applicable | 1 |
| Blocked | 0 |
| Execution Rate | 100% |
| Pass Rate (Applicable Tests) | 80.39% |
| Defects Reported | 10 |

All 52 test cases were executed and results were documented in the Excel workbook.

## Defects Identified

| Defect ID | Defect Description | Severity |
|---|---|---|
| PB-BUG-001 | Browser back navigation displays account information after logout | High |
| PB-BUG-002 | Another user's account details accessible by modifying account ID | High |
| PB-BUG-003 | Zero amount fund transfer accepted | High |
| PB-BUG-004 | Negative amount fund transfer accepted | High |
| PB-BUG-005 | Fund transfer to the same account accepted | Medium |
| PB-BUG-006 | Fund transfer exceeding available balance accepted | High |
| PB-BUG-007 | Blank transfer amount displays internal error | High |
| PB-BUG-008 | Zero amount bill payment accepted | High |
| PB-BUG-009 | Negative amount bill payment accepted | High |
| PB-BUG-010 | Unknown transaction ID displays internal error | Medium |

All 10 defects were documented with reproduction steps, expected results, actual results, severity, priority, and supporting evidence.

**Note:** Defects represent observed behavior in the ParaBank demo application. Some findings may depend on intended business rules.

## Test Artifacts

The project Excel workbook contains four worksheets:

- **Test Plan:** Testing objectives, scope, environment, and approach.
- **Test Cases:** Test scenarios, execution steps, expected results, actual results, and execution status.
- **Defect Log:** Detailed defect reports and evidence links.
- **Execution Summary:** Overall test execution metrics.

The `Bug_Evidence` folder contains screenshots supporting reported defects.

## Testing Environment

- **Application:** ParaBank Demo Banking Application
- **Operating System:** Windows
- **Browser:** Google Chrome
- **Test Data:** Demo banking accounts and fictional user information
- **Execution Method:** Manual testing

## Skills Demonstrated

- Manual Functional Testing
- Test Case Design and Execution
- Positive and Negative Testing
- Defect Identification and Reporting
- Regression and Retesting
- Form Validation Testing
- Banking Application Testing
- Test Documentation
- Test Execution Reporting

## Key Learning Outcomes

This project provided practical experience in testing banking workflows, validating transaction behavior, identifying application defects, and maintaining structured QA documentation.

It also strengthened my understanding of test execution, defect reporting, and evidence management.

## Disclaimer

This is an independent educational testing project performed on the publicly available ParaBank demonstration application. It is not affiliated with or endorsed by Parasoft.

No real banking transactions or customer accounts were used.# ParaBank-Manual-Testing-Project
