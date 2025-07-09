# Daily Report – Day 3 (09-07-2025)

**Tester:** Aleksa Aleksić  
**Project:** DemoBlaze Manual Compatibility Testing  
**Date:** 09.07.2025

---

## Environment:
- **OS:** Ubuntu 22.04 LTS  
- **Browsers:** Chrome 138.0 (Desktop & Emulation), Firefox 128.0 (Desktop)  
- **Devices (Emulated):** iPhone X (iOS Safari), Pixel 5 (Android Chrome)  
- **Tools:** Chrome DevTools Device Toolbar, Firefox Responsive Design Mode, Lightshot, GitHub Issues, TestRail, Lighthouse

---

## Activities:
- Executed **40 desktop test cases**: 20 on Chrome, 20 on Firefox; recorded PASS/FAIL in `ExecutionResults/Module_Results_Chrome_Desktop.md` and `..._Firefox_Desktop.md`.
- Executed **20 mobile test cases**: 10 on iOS (iPhone XII), 10 on Android (Pixel 5); results in `ExecutionResults/Module_Results_IOS.md` and `..._Android.md`.

---

## Exploratory Testing:
- Performed **4 exploratory tests** on edge viewports and unexpected interactions:
  1. Forced landscape on desktop: navigation menu overlaps content.
  2. Rapid Add-to-Cart clicks: duplicate alert generation bug.
  3. Cart persistence after logout and login cycle.
  4. Damaged image URL simulation: placeholder fallback behavior.

---

## Next Steps:
- Document all logged bugs with labels and milestones in GitHub Issues.  
- Author and upload detailed test cases into TestRail.  
- Prepare **Daily Report – Day 4** summarizing mobile defect retests and performance audits.  

---
