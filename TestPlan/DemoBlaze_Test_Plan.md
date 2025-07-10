# Test Plan: DemoBlaze – Manual Compatibility Testing

**Author:** Aleksa Aleksić  
**Date:** 07.07.2025  
**Project:** DemoBlaze Manual Compatibility Testing  
**Base URL:** https://www.demoblaze.com

---

## 1. Introduction  
This document is the formal test plan for manual compatibility testing of the DemoBlaze e‑commerce website. It covers UI and functionality verification across specified desktop and mobile environments. The goal is to identify layout discrepancies, functional issues, and performance bottlenecks, and to produce comprehensive QA artifacts for portfolio inclusion.

---

## 2. Scope

**In Scope:**  
- Cross‑browser and cross‑device testing of core workflows:  
  - **Product Categories** (navigation, pagination)  
  - **Product Detail Pages** (data display, add‑to‑cart)  
  - **Cart Operations** (add/remove items, badge count)  
  - **Order Modal** (order form submission, validations)  
- UI responsiveness and layout consistency  
- Lighthouse performance audits on key pages  
- Defect logging with steps, screenshots, severity

**Out of Scope:**  
- API‑level or automated testing  
- Real payment interactions (demo environment)  
- Extensive performance/load testing beyond Lighthouse  
- Accessibility and security testing

---

## 3. Objectives

- Validate UI consistency and functionality across Chrome, Firefox, and mobile emulations  
- Detect and document layout issues or functional failures per platform  
- Measure performance metrics (load times, render times) and flag >3 s delays  
- Log defects in TestRail/GitHub with reproducible steps and artifacts  
- Deliver structured documentation suitable for a QA portfolio

---

## 4. Roles & Responsibilities

| Role        | Name            | Responsibility                                            |
|-------------|-----------------|----------------------------------------------------------|
| Tester      | Aleksa Aleksić  | Draft plan, execute tests, log defects                   |
| Reviewer    | Self            | Review artifacts, provide feedback                       |
| Stakeholder | Product Owner   | Triage defects, review final report                      |

---

## 5. Test Items

| Module              | Description                                                   |
|---------------------|---------------------------------------------------------------|
| Product Categories  | Navigation links, category filtering, pagination              |
| Product Detail      | Product information, images, "Add to cart" action            |
| Cart                | Item list, quantity, remove action, badge count persistence    |
| Order Modal         | Form fields (Name, Country, City, Credit Card, Month, Year), validations, submission |

---

## 6. Test Approach & Strategy

1. **Test Types:** Compatibility, functional, exploratory, negative boundary  
2. **Design:** Risk‑based covering happy paths and error flows  
3. **Data‑driven:** Use test_users.txt and varied input scenarios  
4. **Execution Order:**  
   1. Categories → 2. Detail → 3. Cart → 4. Order Modal → 5. Performance  
5. **Platforms:**  
   - **Desktop:** Chrome (latest), Firefox (latest)  
   - **Mobile Emulation:** Chrome DevTools (iOS Safari, Android Chrome)  
6. **Defect Management:** TestRail for test cases/results, GitHub Issues for bug tracking  
7. **Performance:** Lighthouse audits per page; record metrics in daily reports

---

## 7. Environment & Tools

- **Browsers:** Chrome (latest), Firefox (latest)  
- **Mobile Emulation:** Chrome DevTools Device Toolbar (iPhone XII, Pixel 5)  
- **Test Data:**  
  - `TestData/test_users.txt` (credentials)  
- **Test Cases & Execution:** Markdown (`TestCases/DemoBlaze_Test_Cases.md`) and TestRail  
- **Bug Tracking:** GitHub Issues  
- **Screenshots:** Lightshot or Snagit  
- **Performance:** Lighthouse (CLI or DevTools)  
- **VCS & Repo:** Git + GitHub (`DemoBlazeTesting`)

## 8. Entry Criteria

- Folder structure established in repository  
- Browsers and tools installed and configured  
- Test data file created  
- Test case template available in TestRail  
- GitHub Issues board ready

---

## 9. Exit Criteria

- All planned test cases executed with PASS/FAIL in TestRail  
- Defects logged with complete details and screenshots  
- Performance audit results recorded  
- Daily reports completed  
- Final summary report drafted

---

## 10. Risks & Mitigation

| Risk                                    | Likelihood | Impact | Mitigation                                     |
|-----------------------------------------|------------|--------|------------------------------------------------|
| Site layout changes may break tests     | Medium     | High   | Verify version daily; update test steps        |
| Flaky behavior in mobile emulation      | Low        | Medium | Cross‑check on desktop or real devices         |
| Slow page loads under emulation         | Medium     | Medium | Record and highlight in performance reports    |
| Incomplete test data coverage           | Low        | Medium | Include negative and boundary input scenarios |

---

## 11. Deliverables

- **Test Plan:** `TestPlan/DemoBlaze_Test_Plan.md`  
- **Test Cases:** `TestCases/DemoBlaze_Test_Cases.md` (Markdown) and in TestRail  
- **Test Data:** `TestData/test_users.txt`  
- **Execution Evidence:** Screenshots and logs in `ExecutionResults/`  
- **Bug Reports:** GitHub Issues  
- **Daily Reports:** `Reports/Daily_Report_DD-MM-YYYY.md`  
- **Final Report:** `Reports/Final_Report.md`

## 12. Schedule 

| Day  | Activity                                       | Duration  |
|------|------------------------------------------------|-----------|
| 1    | Setup & initial planning; create test users; draft first 10 cases | 4 h       |
| 2    | Complete all compatibility test cases in TestRail                 | 4 h       |
| 3    | Execute desktop tests (Chrome, Firefox); log defects             | 5 h       |
| 4    | Execute mobile emulation tests (iOS, Android); log defects       | 5 h       |
| 5    | Performance audits (Lighthouse); exploratory testing; retests     | 4 h       |
| 6    | Finalize execution results; organize issues; draft final report   | 5 h       |
