# Final Report – DemoBlaze Manual Compatibility Testing Project

**Project:** Manual Compatibility and Functional UI Testing of Demoblaze E-Commerce Platform
**Tester:** Aleksa Aleksić
**Duration:** 07-07-2025 to 12-07-2025
**Base URL:** [https://www.demoblaze.com](https://www.demoblaze.com)

---

## 1. Introduction

This report documents the manual compatibility testing of the Demoblaze e-commerce website, executed over six workdays. A total of **60 test cases** were designed and executed across desktop (Chrome & Firefox) and mobile (iOS & Android emulation) platforms. The focus was on UI consistency, functional behavior, error handling, and performance insights via Lighthouse audits.

Key activities included structured test case development, execution logging, defect reporting in GitHub Issues, exploratory testing, and performance measurement. All tests were executed manually using Chrome and Firefox, with detailed Markdown logs and screenshots for all failing scenarios.

This project was designed to demonstrate comprehensive manual testing skills suitable for junior QA roles, emphasizing real-world compatibility and functionality scenarios.

---

## 2. Scope & Objectives

**Scope:**

- Manual testing of core modules:
  - Product Categories (Navigation, Pagination, Filtering)
  - Product Detail Pages
  - Shopping Cart (Add/Remove, Badge Persistence)
  - Order Modal (Form Validation, Layout)
  - Responsive Layout across devices
- Performance audits on key pages (Home, Product Detail, Cart)

**Objectives:**

1. Ensure consistent UI and functionality across browsers and emulated mobile devices.
2. Identify and report compatibility and functional defects with detailed reproduction steps.
3. Document performance metrics to highlight potential optimization areas.
4. Produce a comprehensive set of QA artifacts suitable for a junior QA portfolio.

---

## 3. Test Environment & Tools

**Operating System:**  Ubuntu 22.04 LTS
**Browsers:**

- Desktop: Chrome 138.0.7204.100 & Firefox 140.0.4
- Mobile Emulation: iOS Safari (iPhone XII Pro), Android Chrome (Pixel 7) via Chrome DevTools

**Tools & Utilities:**

- Test Management: TestRail & Markdown files
- Defect Tracking: GitHub Issues
- Screenshots: Lightshot and LibreOffice Draw
- Performance Audits: Chrome Lighthouse
- Documentation: VS Code, Markdown

---

## 4. Folder Structure & Artifacts

Below is the main project folder structure for organized test artifacts:

````
~/DemoblazeTesting/
├── TestPlan/
│   └── Demoblaze_Test_Plan.md
├── TestCases/
│   ├── IOS_Test_Cases.md
│   ├── DemoBlaze_Test_Cases.md
│   ├── Desktop_Test_Cases.md
│   └── Android_Test_Cases.md
│   └── TestRail_Screenshots/
├── ExecutionResults/
│   ├── Execution_Results_Mozilla_Desktop.md
│   ├── Execution_Results_Lighthouse.md
│   ├── Execution_Results_IOS.md
│   ├── Execution_Results_Desktop.md
│   ├── Execution_Results_Chrome_Desktop.md
│   ├── Defect_Retest.md
│   ├── Execution_Results_Android.md
│   └── Defect_Report_Screenshots/
├── Reports/
│   ├── Daily_Report_07-07-2025.md
│   ├── Daily_Report_08-07-2025.md
│   ├── Daily_Report_09-07-2025.md
│   ├── Daily_Report_10-07-2025.md
│   ├── Daily_Report_11-07-2025.md
│   ├── Final_Report.md
│   └── Lighthouse_Reports/
├── TestData/
│   └── text_users.txt
└── README.md  

---

---

## 5. Test Case Coverage

A total of **60 test cases** were implemented and executed:

| Module                   | TC Count |
| ------------------------ | -------- |
| Mozilla Firefox Desktop  | 20       |
| Google Chrome Desktop    | 20       |
| Andorid (Mobile)         | 10       |
| iOS (Mobile)             | 10       |

Test cases included positive, negative, and boundary scenarios, with full documentation of preconditions, steps, expected and actual results, status, priority, and type.

---

## 6. Execution Summary

| Module               | Executed | PASS   | FAIL   | Bugs Reported |
| -------------------- | -------- | ------ | ------ | ----------- |
| Categories (Chrome)  | 20       | 17     | 3      | 3           |
| Categories (Firefox) | 20       | 17     | 3      | 3           |
| Mobile iOS           | 10       | 8      | 2      | 2           |
| Mobile Android       | 10       | 8      | 2      | 2           |
| **Total**            | **60**   | **50** | **10** | **10**      |

- **Total Execution Time:** \~30 hours
- **Total Bugs Reported:** 10
- **Retest Outcome:** 3 Fixed, 7 Still Reproducible

---

## 7. Defect Overview

All defects were logged in GitHub Issues with steps, severity, priority, and screenshots. Key issues included:

- JavaScript errors on category page (Monitors)
- Add-to-cart failures (no alert, badge update issues)
- Truncated product descriptions in Firefox
- Mobile layout overlaps in landscape orientation
- Cart badge persistence issues on refresh

---

## 8. Performance Audit Results

Performance audits were conducted using Lighthouse on Home, Product Detail, and Cart pages in both Desktop and Mobile modes. Summary of performance scores:

| Page           | Desktop Score | Mobile Score |
| -------------- | ------------- | ------------ |
| Home           | 91            | 84           |
| Product Detail | 89            | 78           |
| Cart           | 86            | 73           |

Detailed metrics and recommendations are available in `ExecutionResults/Performance_Audit_Results.md`.

---

## 9. Recommendations

1. **Fix JavaScript rendering issues** on category pages to ensure consistent product loading.
2. **Implement responsive fixes** for mobile layouts in landscape mode (grid and modal alignment).
3. **Enhance form validation** in the order modal (required fields, error messaging).
4. **Improve badge persistence** logic in the shopping cart to maintain state.
5. **Optimize performance** by compressing images, deferring non-critical JS, and lazy-loading content.

Addressing these will significantly improve user experience and platform stability.

---

## 10. Conclusion

This manual compatibility testing engagement for Demoblaze has successfully validated critical UI and functional aspects across desktop and mobile environments. The structured test approach, thorough documentation, and performance insights provide a solid foundation for future iterations and automation. All artifacts and reports are traceable in the GitHub repository, demonstrating a professional and comprehensive QA process.

```