# ExecutionResults/Module_Results_IOS.md

**OS:** Ubuntu 22.04 LTS  
**Emulated Device:** iPhone XII  
**Date of Execution:** 08-07-2025

---

## 📱 Mobile Test Execution – iOS Safari Emulation

- ✅ **8 test cases passed** successfully.  
- ❌ **2 test cases failed** (TC_MOB_iOS_03, TC_MOB_iOS_08)

---

### TC_MOB_iOS_01: Verify hamburger menu toggles visibility  
**Start Time:** 12:30  
**Test Steps:**  
1. Tap the hamburger menu icon.  
2. Observe menu expansion.  
3. Tap the icon again.  
**Result:** PASS  
**Actual:** Menu expands and collapses as expected.  
**End Time:** 12:32

---

### TC_MOB_iOS_02: Verify category links accessible in hamburger menu  
**Start Time:** 12:33  
**Test Steps:**  
1. Expand hamburger menu.  
2. Tap "Laptops" link.  
**Result:** PASS  
**Actual:** User is redirected to the Laptops category page.  
**End Time:** 12:35

---

### TC_MOB_iOS_03: Verify responsive grid on homepage  
**Start Time:** 12:36  
**Test Steps:**  
1. Rotate device orientation.  
2. Observe product grid layout.  
**Result:** FAIL  
**Actual:** Grid fails to reflow correctly in landscape; overlaps observed.  
**End Time:** 12:39
**Screenshot:**

![Screenshot](/ExecutionResults/Defect_Report_Screenshots/TC_MOB_iOS_03_fail.png)

---

### TC_MOB_iOS_04: Verify pagination buttons in mobile view  
**Start Time:** 12:39  
**Test Steps:**  
1. Scroll to pagination section in Phones.  
2. Tap "Next".  
**Result:** PASS  
**Actual:** Products on next page loaded as expected.  
**End Time:** 12:41

---

### TC_MOB_iOS_05: Verify product card layout on iPhone X emulation  
**Start Time:** 12:42  
**Test Steps:**  
1. Go to Laptops category.  
2. Check layout of product cards.  
**Result:** PASS  
**Actual:** Card layout adjusts properly, all elements visible.  
**End Time:** 12:45

---

### TC_MOB_iOS_06: Verify "Add to cart" alert positioning  
**Start Time:** 12:45  
**Test Steps:**  
1. Tap "Add to cart" for a product.  
2. Observe alert position.  
**Result:** PASS  
**Actual:** Alert appears centered and fully visible.  
**End Time:** 12:47

---

### TC_MOB_iOS_07: Verify order modal displays correctly  
**Start Time:** 12:48  
**Test Steps:**  
1. Add item to cart.  
2. Click "Cart" → Tap "Place Order".  
**Result:** PASS  
**Actual:** Order modal appears centered and is scrollable.  
**End Time:** 12:50

---

### TC_MOB_iOS_08: Verify form field alignment in order modal  
**Start Time:** 12:51  
**Test Steps:**  
1. Open order modal.  
2. Observe label/input alignment.  
**Result:** FAIL  
**Actual:** Labels for ZIP code and Name fields misaligned on iPhone X resolution.    
**End Time:** 12:54
**Screenshot:**

![Screenshot](/ExecutionResults/Defect_Report_Screenshots/TC_MOB_iOS_08_fail.png)

---

### TC_MOB_iOS_09: Verify modal scroll behavior on small screens  
**Start Time:** 12:54  
**Test Steps:**  
1. Open order modal.  
2. Attempt to scroll down to submit button.  
**Result:** PASS  
**Actual:** Content scrolls properly; no truncation.  
**End Time:** 12:57

---

### TC_MOB_iOS_10: Verify responsive page title visibility  
**Start Time:** 12:57  
**Test Steps:**  
1. Load any product or category page.  
2. Check browser title bar in emulated tab.  
**Result:** PASS  
**Actual:** Title renders clearly and is not truncated.  
**End Time:** 13:02

---
