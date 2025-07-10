# Daily Report – Day 4 (10-07-2025)

**Tester:** Aleksa Aleksić  
**Project:** DemoBlaze Manual Compatibility Testing  
**Date:** 10.07.2025

---

## Environment:
- **OS:** Ubuntu 22.04 LTS  
- **Browsers:** Chrome 138.0.7204.100 (Desktop & Emulation), Firefox 140.0 (Desktop)  
- **Devices (Emulated):** iPhone XII (iOS Safari), Pixel 5 (Android Chrome)  
- **Tools:** Chrome DevTools Device Toolbar, Firefox Responsive Design Mode, Lightshot, GitHub Issues, TestRail, Lighthouse

---

## Activities:
- Performed **performance audit load testing** using Lighthouse and Lightshot, generated audit reports in `.html` format for multiple pages.
- Created **10 defect reports** documenting discovered bugs (without screenshots yet).
- Added **3 new exploratory tests** focusing on edge cases and UI behavior:
  1. Tested slow network simulation (3G) to verify site loading and responsiveness.
  2. Attempted multiple simultaneous product additions to cart to check for race conditions.
  3. Tested currency switcher behavior while products are in the cart.

---

## Exploratory Testing Summary:
- Slow network mode revealed delayed image loading but no functional break.
- Multiple add-to-cart clicks caused cart quantity desync in some cases.
- Currency switcher did not update cart totals properly in a few instances.

---

## Next Steps:
- Retest all logged bugs and verify fixes or reproduce issues.
- Capture and attach **screenshots for all defect reports** in GitHub Issues.
- Author detailed **test cases in TestRail** based on test results and exploratory findings.
- Prepare **Daily Report – Day 5** covering retests, screenshots, and further exploratory testing.
