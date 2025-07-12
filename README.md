# DemoBlaze – Manual E‑commerce Compatibility Testing Project

A comprehensive manual QA project demonstrating end‑to‑end functional, compatibility, and performance testing of the DemoBlaze e‑commerce demo application.

---

## Project Overview

**DemoBlaze** is a public demo e‑commerce site used for QA learning. This project covers seven days of manual testing across desktop and mobile environments, focusing on:

- **Product Categories:** Navigation, pagination, filtering accuracy  
- **Product Detail Pages:** Content verification, image loading, UI layout  
- **Shopping Cart:** Add/remove functions, badge count, empty‑cart handling  
- **Order Modal (Mobile):** Form validation, layout alignment, scrolling behavior  
- **Responsive Layout Checks:** Cross‑device consistency using iPhone XII Pro & Pixel 7 emulations  
- **Performance Audits:** Lighthouse analysis for Home, Product Detail, and Cart pages  

**60 test cases executed**  
**10 defects logged**  
**Performance scores collected and analyzed**

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

## Test Environment & Tools

- **OS:** Ubuntu 22.04 LTS  
- **Browsers:**  
  - Chrome 138.0.7204.100  
  - Firefox 140.0.4  
- **Mobile Emulation:**  
  - iPhone XII Pro  
  - Pixel 7
- **Test Case Management:** Markdown & TestRail  
- **Bug Tracking:** GitHub Issues  
- **Screenshots:** Lightshot + LibreOffice Draw  
- **Performance Audits:** Google Lighthouse  
- **Documentation:** Visual Studio Code & Markdown

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

## How to Navigate the Repo

1. **Clone Repository:**
   ```bash
   git clone https://github.com/aleksa3009/DemoblazeTesting.git
   cd DemoblazeTesting
   ```

2. **Start with the Test Plan:**  
   `TestPlan/Demoblaze_Test_Plan.md`

3. **View Test Cases by Module:**  
   - Desktop: `Desktop_Test_Cases.md`  
   - Mobile: `IOS_Test_Cases.md`, `Android_Test_Cases.md`  

4. **Review Execution Logs:**  
   Folder: `ExecutionResults/`  

5. **Inspect Failures:**  
   Folder: `Defect_Report_Screenshots/`

6. **Explore Performance Analysis:**  
   Folder: `ExecutionResults/Execution_Results_Lighthouse.md`

7. **Final Report & Summary:**  
   `Reports/Final_Report.md`

---

## Contact

Maintainer: **Aleksa Aleksić**  
[askela3009@gmail.com](mailto:askela3009@gmail.com)

---

*This README reflects a structured, professional approach to manual testing and is intended as a showcase for junior QA positions or training assessments.*
