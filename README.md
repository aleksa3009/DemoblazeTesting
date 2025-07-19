# DemoBlaze – Manual E-commerce Compatibility Testing Project

A comprehensive manual QA project showcasing end-to-end functional, compatibility, and performance testing of the DemoBlaze demo e-commerce site ([https://demoblaze.com/](https://demoblaze.com/)).

---

## Project Overview

This repository contains all deliverables from a seven-day manual testing engagement on DemoBlaze, including:

- **Product Categories:** Navigation, pagination, filtering accuracy  
- **Product Detail Pages:** Content verification, image loading, UI layout  
- **Shopping Cart:** Add/remove functionality, badge count, empty-cart handling  
- **Order Modal (Mobile):** Form validation, layout alignment, scrolling behavior  
- **Responsive Layout Checks:** Cross-device consistency using iPhone XII Pro & Pixel 7 emulations  
- **Performance Audits:** Google Lighthouse analysis of Home, Product Detail, and Cart pages  

A total of **60 structured test cases** were executed, and defects were logged accordingly.

**Important Notice:**  
The DemoBlaze site has been **non-functional since July 17, 2025**. Due to this, further updates or fixes to this project are not possible.

---

## Repository Structure

```bash
DemoblazeTesting/
├── TestPlan/                       # Test strategy, scope & objectives
│   └── Demoblaze_Test_Plan.md
├── TestCases/                      # Manual test cases (Markdown & TestRail screenshots)
│   ├── DemoBlaze_Test_Cases.md
│   ├── Desktop_Test_Cases.md
│   ├── IOS_Test_Cases.md
│   ├── Android_Test_Cases.md
│   └── TestRail_Screenshots/
├── ExecutionResults/               # Execution logs & failure screenshots
│   ├── Execution_Results_Chrome_Desktop.md
│   ├── Execution_Results_Mozilla_Desktop.md
│   ├── Execution_Results_IOS.md
│   ├── Execution_Results_Android.md
│   ├── Execution_Results_Lighthouse.md
│   ├── Defect_Retest.md
│   └── Defect_Report_Screenshots/
├── Reports/                        # Daily logs and final report
│   ├── Daily_Report_07-07-2025.md
│   ├── Daily_Report_08-07-2025.md
│   ├── Daily_Report_09-07-2025.md
│   ├── Daily_Report_10-07-2025.md
│   ├── Daily_Report_11-07-2025.md
│   ├── Lighthouse_Reports/
│   └── Final_Report.md
├── TestData/
│   └── text_users.txt
└── README.md                       # Project overview and instructions
```

---

## Tools & Environment

- **Operating System:** Ubuntu 22.04 LTS  
- **Browsers:** Chrome 138.0.7204.100, Firefox 140.0.4  
- **Mobile Emulation:** iPhone XII Pro, Pixel 7  
- **Test Management:** Markdown files, TestRail  
- **Bug Tracking:** GitHub Issues  
- **Screenshots:** Lightshot & LibreOffice Draw  
- **Performance Audits:** Google Lighthouse  
- **Version Control:** Git & GitHub  

---

## Test Execution Summary

| Platform/Browser     | Test Cases | PASS   | FAIL   | Bugs Logged    |
|----------------------|------------|--------|--------|----------------|
| Desktop – Chrome     | 20         | 17     | 3      | 3              |
| Desktop – Firefox    | 20         | 17     | 3      | 3              |
| Mobile – iOS (Safari)| 10         | 8      | 2      | 2              |
| Mobile – Android     | 10         | 8      | 2      | 2              |
| **Total**            | **60**     | **50** | **10** | **10**         |

**Estimated Effort:** ~30 hours  
**Average Test Case Duration:** ~10 min  

---

## Defect Summary

Defects were logged in GitHub with full detail:

- **Critical:**  
  - JS errors on category page (Monitors)  
  - Broken back‑navigation on mobile  

- **Major:**  
  - Cart badge not updating  
  - Add-to-cart failures without alert  
  - Layout misalignment on small screens  

- **Medium/Low:**  
  - Truncated product description (Firefox)  
  - Static page titles  
  - Lighthouse CLS warnings  

[GitHub Issues](https://github.com/aleksa3009/DemoblazeTesting/issues)

---

## Lighthouse Performance Overview

| Page           | Desktop | Mobile |
|----------------|---------|--------|
| Home           | 91      | 84     |
| Product Detail | 89      | 78     |
| Cart           | 86      | 73     |

**Optimization Tips:**

- Compress large images  
- Lazy-load offscreen content  
- Defer non‑essential JS  
- Define image dimensions to reduce layout shift  

See: `ExecutionResults/Execution_Results_Lighthouse.md`

---

## Transparency Note

This project is part of a personal QA portfolio. Some defects reported in this repository were intentionally fabricated for demonstration purposes, in order to showcase defect documentation, reporting skills, and test case design. Given the DemoBlaze site has been non-functional since July 17, 2025, no further fixes or updates can be applied.

---

## Conclusion

This project demonstrates a structured manual testing approach with comprehensive documentation, covering functional, compatibility, and performance aspects of DemoBlaze. Despite site unavailability, the artifacts showcase solid QA methodology and reporting suitable for junior QA portfolios.

---

End of README