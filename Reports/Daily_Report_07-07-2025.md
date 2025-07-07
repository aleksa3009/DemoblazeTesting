# Daily Report – 07‑07-2025 (Day 1)

---

## Activities:
- Created project repository `DemoBlazeTesting` on GitHub with full folder structure:
  ```
  DemoblazeTesting/
  ├── TestPlan/
  ├── TestCases/
  ├── TestData/
  ├── ExecutionResults/
  └── Reports/
  ```
- Drafted and committed **Test Plan** (`TestPlan/DemoBlaze_Test_Plan.md`) covering scope, objectives, roles, tools, risks, and schedule.
- Generated **Desktop Test Cases** document (`DemoBlaze_Desktop_TC`) with 10 detailed test cases for navigation, pagination, add‑to‑cart, and product details.
- Created initial **Test Data** file (`TestData/test_users.txt`) with two user credentials for compatibility testing.
- Initialized **GitHub Issues** board template for bug logging, including fields for steps, severity, and attachments.
- Prepared **Daily Report** template in `Reports/Daily_Report_07-07-2025.md`.

---

## Environment:
- **OS:** Ubuntu 22.04 LTS  
- **Browsers:** Chrome (latest) & Firefox (latest) on desktop; Chrome DevTools emulating iPhone XII & Pixel 5  
- **Tools:** VS Code, Lightshot, Git/GitHub, TestRail (for test management), Lighthouse (for performance audits)

---

## Issues:
- No critical blockers; all tools installed and configured smoothly.
- Minor note: need to confirm mobile emulation viewport dimensions for non‑standard screen sizes.

---

## Next Steps (Day 2):
1. **Test Case Finalization:** Import and map all 40 test cases into TestRail.
2. **Execution – Desktop:** Run the first 10 desktop test cases on Chrome & Firefox; log results and any defects.
3. **Execution – Mobile:** Execute first 5 iOS emulation cases; capture screenshots of any layout anomalies.
4. **Performance Audits:** Run Lighthouse on homepage and product listing pages; record load/render metrics.
5. **Daily Report:** Document findings and defects in `Reports/Daily_Report_08-07-2025.md`.
