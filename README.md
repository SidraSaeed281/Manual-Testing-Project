# Manual QA Testing– SauceDemo

This repository contains a manual QA testing project performed on the practice site SauceDemo.
It demonstrates the ability to design, document, and organize manual test cases, scenarios, execution results, and bug reports using industry‑standard QA documentation formats.

The goal of this project is to showcase QA practices for Register, Login, Forgot Password, and Cart modules, covering functional flows, input validation (including password length checks), usability, and defect tracking.

## Repository Structure

```manual-testing-saucedemo/
│
├── srs/                     # Software Requirement Specification
│   └── SRS_Document.pdf
│
├── test-cases/              # Detailed test cases
│   ├── register.md
│   ├── login.md
│   ├── forgot-password.md
│   ├── cart.md
│   └── README.md
│
├── test-scenarios/          # Scenario outlines
│   └── scenarios.md
│
├── execution-results/       # Test execution sheets
│   ├── forgot-password-execution.md
│   ├── cart-execution.md
│   └── README.md
│
├── bug-reports/             # Bug reports
│   ├── cart-bug-report.md
│   ├── register-bug-report.md
│   └── README.md
│
└── README.md

```

## Bug Report – Cart does not update quantity
- **ID:** CART_BUG_001  
- **Title:** Cart does not provide a decrease quantity option  
- **Severity:** High  
- **Priority:** High  

**Steps to Reproduce**
1. Login with valid user  
2. Add “Shoes” to the cart  
3. Navigate to cart  
4. Try to decrease item quantity  

**Expected Result**
User should be able to increase **and** decrease item quantity.  

**Actual Result**
Quantity only increases; no button/function to decrease.

 ## Testing Types Performed

- Functional Testing → Verified Register, Login, Forgot Password, and Cart features.
- Validation Testing → Checked input fields and error handling (including password length validation).
- Usability Testing → Ensured user‑friendly flows (cart icon count, reset link usability).
- Regression Testing → Re‑ran cases after fixes to confirm stability.
- Positive & Negative Testing → Covered both valid and invalid input scenarios.

```	

Each file is named after the corresponding bug to maintain consistency.
