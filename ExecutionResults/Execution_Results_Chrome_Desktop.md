# ExecutionResults/Module_Results_Desktop_Chrome.md

**Browser:** Chrome 137.0.7151.119  
**OS:** Ubuntu 22.04 LTS  
**Date of Execution:** 2025-07-08  

---

## 🖥️ Desktop Test Execution – Chrome

A total of **20 test cases** were executed on the Chrome browser for desktop UI compatibility. Test coverage included category navigation, pagination, product details, and add-to-cart operations.

- ✅ **17 test cases passed** successfully.
- ❌ **3 test cases failed** due to functional or UI issues.
- 🧪 Browser: Chrome (latest, stable), Ubuntu Linux.

---

### TC_DESK_CAT_01: Verify navigation to "Phones" category  
**Start Time:** 11:15  
**Test Steps:**  
1. Launch homepage.  
2. Click "Phones" on left panel.  
**Result:** PASS  
**Actual:** Phones filtered and listed properly.  
**End Time:** 11:17

---

### TC_DESK_CAT_02: Verify navigation to "Laptops" category  
**Start Time:** 11:18  
**Test Steps:**  
1. Click "Laptops".  
**Result:** PASS  
**Actual:** Laptops shown correctly.  
**End Time:** 11:20

---

### TC_DESK_CAT_03: Verify navigation to "Monitors" category  
**Start Time:** 11:21  
**Test Steps:**  
1. Click "Monitors".  
**Result:** PASS  
**Actual:** 2 monitors listed; layout as expected.  
**End Time:** 11:23

---

### TC_DESK_CAT_04: Verify pagination next page  
**Start Time:** 11:24  
**Test Steps:**  
1. Click "Next"  
2. Confirm new products shown.  
**Result:** PASS  
**Actual:** Page advanced successfully.  
**End Time:** 11:26

---

### TC_DESK_CAT_05: Verify pagination previous page  
**Start Time:** 11:27  
**Test Steps:**  
1. Click "Previous"  
2. Confirm old product set restored.  
**Result:** PASS  
**Actual:** Returned to original product view.  
**End Time:** 11:29

---

### TC_DESK_CAT_06: Verify pagination buttons disabled state  
**Start Time:** 11:30  
**Test Steps:**  
1. On first page, try clicking "Previous".  
**Result:** PASS  
**Actual:** Button inactive as expected.  
**End Time:** 11:32

---

### TC_DESK_CAT_07: Verify adding a phone to cart from category listing  
**Start Time:** 11:33  
**Test Steps:**  
1. Click on phone product.  
2. Add to cart.  
**Result:** PASS  
**Actual:** Alert appeared. Product added.  
**End Time:** 11:35

---

### TC_DESK_CAT_08: Verify adding a laptop to cart from category listing  
**Start Time:** 11:36  
**Test Steps:**  
1. Choose laptop.  
2. Add to cart.  
**Result:** PASS  
**Actual:** Cart updated successfully.  
**End Time:** 11:38

---

### TC_DESK_CAT_09: Verify adding multiple items from different categories  
**Start Time:** 11:39  
**Test Steps:**  
1. Add one phone and one monitor.  
2. Go to cart.  
**Result:** PASS  
**Actual:** Items visible with correct prices.  
**End Time:** 11:42

---

### TC_DESK_CAT_10: Verify removing item from cart badge via category listing  
**Start Time:** 11:43  
**Test Steps:**  
1. Add an item.  
2. Remove it manually.  
**Result:** FAIL  
**Actual:** Cart badge remained at 1 even after item was removed.   
**End Time:** 11:46
**Screenshot:**

![Screenshot](/ExecutionResults/Defect_Report_Screenshots/TC_Desk_10_fail.png)

---

### TC_DESK_CAT_11: Verify product detail displays correct name  
**Start Time:** 11:47  
**Test Steps:**  
1. View product detail.  
**Result:** PASS  
**Actual:** Name matches.  
**End Time:** 11:49

---

### TC_DESK_CAT_12: Verify product detail displays correct price  
**Start Time:** 11:50  
**Test Steps:**  
1. View price on detail page.  
**Result:** PASS  
**Actual:** Matches category view.  
**End Time:** 11:52

---

### TC_DESK_CAT_13: Verify product images load properly  
**Start Time:** 11:53  
**Test Steps:**  
1. Open product page.  
2. Inspect image.  
**Result:** PASS  
**Actual:** Image loads without error.  
**End Time:** 11:55

---

### TC_DESK_CAT_14: Verify "Add to cart" from product detail page  
**Start Time:** 11:56  
**Test Steps:**  
1. Add to cart from detail page.  
**Result:** PASS  
**Actual:** Item added, cart updated.  
**End Time:** 11:59

---

### TC_DESK_CAT_15: Verify back navigation from detail to listing  
**Start Time:** 12:00  
**Test Steps:**  
1. Use browser back button.  
**Result:** PASS  
**Actual:** Returned to product list.  
**End Time:** 12:02

---

### TC_DESK_CAT_16: Verify currency consistency across pages  
**Start Time:** 12:03  
**Test Steps:**  
1. Compare price symbols.  
**Result:** PASS  
**Actual:** USD shown throughout.  
**End Time:** 12:05

---

### TC_DESK_CAT_17: Verify product description text displays correctly  
**Start Time:** 12:06  
**Test Steps:**  
1. Read description area.  
**Result:** PASS  
**Actual:** Text renders as expected.  
**End Time:** 12:08

---

### TC_DESK_CAT_18: Verify cart badge persists after page refresh  
**Start Time:** 12:09  
**Test Steps:**  
1. Refresh page after adding item.  
**Result:** FAIL  
**Actual:** Badge reset to 0; cart was empty.  
**End Time:**12:12
**Screenshot:**

![Screenshot](/ExecutionResults/Defect_Report_Screenshots/TC_Desk_18_fail.png)

---

### TC_DESK_CAT_19: Verify URL changes on category selection  
**Start Time:** 12:13  
**Test Steps:**  
1. Click between categories.  
2. Check URL.  
**Result:** PASS  
**Actual:** URL hash changes correctly.  
**End Time:** 12:15

---

### TC_DESK_CAT_20: Verify page title updates per category  
**Start Time:** 12:16  
**Test Steps:**  
1. View browser title bar.  
**Result:** FAIL  
**Actual:** Title remained static as "STORE" regardless of selected category.   
**End Time:** 12:18
**Screenshot:**

![Screenshot](/ExecutionResults/Defect_Report_Screenshots/TC_Desk_20_fail.png)

---
