# ExecutionResults/Module_Results_Android.md

**OS:** Ubuntu 22.04 LTS  
**Emulated Devices:** Pixel 5 (Android Chrome)  
**Date of Execution:** 08-07-2025  

---

## 📱 Mobile Test Execution – Android Chrome Emulation

- ✅ **8 test cases passed** successfully.  
- ❌ **2 test cases failed** (TC_MOB_AND_03, TC_MOB_AND_08).

---

### TC_MOB_AND_01: Verify hamburger menu toggles visibility  
**Start Time:** 13:02  
**Test Steps:**  
1. Load homepage.  
2. Tap hamburger menu icon.  
3. Confirm it expands.  
4. Tap again to collapse.  
**Result:** ✅ PASS  
**Actual:** Menu expands and collapses without delay.  
**End Time:** 13:05

---

### TC_MOB_AND_02: Verify category navigation from hamburger menu  
**Start Time:** 13:05  
**Test Steps:**  
1. Open hamburger menu.  
2. Tap "Monitors".  
**Result:** ✅ PASS  
**Actual:** Navigated to Monitors category page.  
**End Time:** 13:07

---

### TC_MOB_AND_03: Verify responsive layout on Pixel 5 emulation  
**Start Time:** 13:07  
**Test Steps:**  
1. Load homepage in portrait mode.  
2. Rotate to landscape.  
3. Observe product grid.  
**Result:** ❌ FAIL  
**Actual:** Grid misaligned in landscape mode, overlapping 2 product cards.  
**End Time:** 13:09
**Screenshot:**

![Screenshot](/ExecutionResults/Defect_Report_Screenshots/TC_Android_03_fail.png)


---

### TC_MOB_AND_04: Verify pagination in Android emulation  
**Start Time:** 13:10  
**Test Steps:**  
1. Scroll to pagination.  
2. Tap "Next".  
**Result:** ✅ PASS  
**Actual:** Loads next product set correctly.  
**End Time:** 13:13

---

### TC_MOB_AND_05: Verify product card layout on Android  
**Start Time:** 13:13  
**Test Steps:**  
1. Observe product card.  
**Result:** ✅ PASS  
**Actual:** Card is fully visible; no UI issues found.  
**End Time:** 13:14

---

### TC_MOB_AND_06: Verify "Add to cart" alert on Android  
**Start Time:** 13:15  
**Test Steps:**  
1. Add an item to cart.  
**Result:** ✅ PASS  
**Actual:** Alert displays correctly, centered.  
**End Time:** 13:17

---

### TC_MOB_AND_07: Verify order modal placement on Android  
**Start Time:** 13:17  
**Test Steps:**  
1. Open cart.  
2. Tap "Place Order".  
**Result:** ✅ PASS  
**Actual:** Modal renders fully, no layout issues.  
**End Time:** 13:20

---

### TC_MOB_AND_08: Verify form field alignment in order modal  
**Start Time:** 13:21  
**Test Steps:**  
1. Open order modal.  
2. Observe label/field alignment.  
**Result:** ❌ FAIL  
**Actual:** Field labels are shifted and misaligned on smaller widths.   
**End Time:** 13:25
**Screenshot:**

![Screenshot](/ExecutionResults/Defect_Report_Screenshots/TC_Android_08_fail.png)

---

### TC_MOB_AND_09: Verify modal scroll on Android  
**Start Time:** 13:25  
**Test Steps:**  
1. Swipe vertically in modal.  
**Result:** ✅ PASS  
**Actual:** Scroll is fluid; all form fields reachable.  
**End Time:** 13:29

---

### TC_MOB_AND_10: Verify responsive page title visibility  
**Start Time:** 13:29  
**Test Steps:**  
1. Check page title from browser tab.  
**Result:** ✅ PASS  
**Actual:** Title is visible and not truncated.  
**End Time:** 13:33

---

Summary:  
- Total Test Cases: 10  
- Passed: 8  
- Failed: 2 (detailed bug reports linked)  
- Next steps: Retesting of failed cases after bug fixes.
