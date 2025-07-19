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

# ExecutionResults/Module_Results_Desktop_Firefox.md

**Browser:** Firefox 127.0.1  
**OS:** Ubuntu 22.04 LTS  
**Date of Execution:** 08-07-2025  

---

## 🖥️ Desktop Test Execution – Firefox

A total of **20 test cases** were executed on the Firefox browser as part of desktop compatibility and functional UI testing. The test suite covered product category navigation, pagination, add-to-cart functionality, and product detail pages.

- ✅ **17 test cases passed** successfully.
- ❌ **3 test cases failed** due to rendering issues or inconsistent behavior.

Test data: Default homepage products and two test user accounts from `TestData/test_users.txt`

---

### TC_DESK_CAT_01: Verify navigation to "Phones" category  
**Start Time:** 10:00  
**Test Steps:**  
1. Open homepage  
2. Click "Phones" in left navigation  
**Result:** PASS  
**Actual:** Products filtered correctly and displayed under Phones category.  
**End Time:** 10:02

---

### TC_DESK_CAT_02: Verify navigation to "Laptops" category  
**Start Time:** 10:03  
**Test Steps:**  
1. Click "Laptops" in left menu  
2. Observe page reload and filter results  
**Result:** PASS  
**Actual:** Laptop products correctly listed. No UI overlap.  
**End Time:** 10:05

---

### TC_DESK_CAT_03: Verify navigation to "Monitors" category  
**Start Time:** 10:06  
**Test Steps:**  
1. Click "Monitors" category  
2. Wait for listing to load  
**Result:** FAIL  
**Actual:** No products are displayed; console shows `TypeError: undefined is not iterable`.  
**End Time:** 10:09
**Screenshot:**

![Screenshot](/ExecutionResults/Defect_Report_Screenshots/TC_Desk_03_fail.png)

---

### TC_DESK_CAT_04: Verify pagination next page  
**Start Time:** 10:10  
**Test Steps:**  
1. Scroll to bottom  
2. Click "Next"  
3. Verify new products loaded  
**Result:** PASS  
**Actual:** Page updated with new product set.  
**End Time:** 10:12

---

### TC_DESK_CAT_05: Verify pagination previous page  
**Start Time:** 10:13  
**Test Steps:**  
1. Click "Previous"  
2. Confirm product list returns to original  
**Result:** PASS  
**Actual:** Returns to first set of products.  
**End Time:** 10:15

---

### TC_DESK_CAT_06: Verify pagination buttons disabled state  
**Start Time:** 10:16  
**Test Steps:**  
1. On first page, check if "Previous" is disabled  
**Result:** PASS  
**Actual:** "Previous" button is inactive as expected.  
**End Time:** 10:18

---

### TC_DESK_CAT_07: Verify adding a phone to cart from category listing  
**Start Time:** 10:19  
**Test Steps:**  
1. Select phone from category  
2. Click "Add to cart"  
3. Observe confirmation alert  
**Result:** FAIL  
**Actual:** No alert triggered; cart remains unchanged. Possibly JS issue.   
**End Time:** 10:22
**Screenshot:**

![Screenshot](/ExecutionResults/Defect_Report_Screenshots/TC_Desk_07_fail.png)

---

### TC_DESK_CAT_08: Verify adding a laptop to cart from category listing  
**Start Time:** 10:23  
**Test Steps:**  
1. Choose laptop  
2. Add to cart  
**Result:** PASS  
**Actual:** Alert popup shown; item successfully added.  
**End Time:** 10:25

---

### TC_DESK_CAT_09: Verify adding multiple items from different categories  
**Start Time:** 10:26  
**Test Steps:**  
1. Add phone + laptop  
2. Go to cart page  
**Result:** PASS  
**Actual:** Both items visible in cart with correct prices.  
**End Time:** 10:29

---

### TC_DESK_CAT_10: Verify removing item from cart badge via category listing  
**Start Time:** 10:30  
**Test Steps:**  
1. Add item, then remove from cart  
**Result:** PASS  
**Actual:** Item removed; badge decremented from 1 → 0.  
**End Time:** 10:32

---

### TC_DESK_CAT_11: Verify product detail displays correct name  
**Start Time:** 10:33  
**Test Steps:**  
1. Click item title  
2. Compare name with listing  
**Result:** PASS  
**Actual:** Product name matches listing view.  
**End Time:** 10:35

---

### TC_DESK_CAT_12: Verify product detail displays correct price  
**Start Time:** 10:36  
**Test Steps:**  
1. Open detail page  
2. Verify price  
**Result:** PASS  
**Actual:** Price matches previous category view and cart.  
**End Time:** 10:38

---

### TC_DESK_CAT_13: Verify product images load properly  
**Start Time:** 10:39  
**Test Steps:**  
1. Click product  
2. Wait for image to load  
**Result:** PASS  
**Actual:** Image loads with correct resolution. No broken links.  
**End Time:** 10:41

---

### TC_DESK_CAT_14: Verify "Add to cart" from product detail page  
**Start Time:** 10:42  
**Test Steps:**  
1. On detail page, click "Add to cart"  
**Result:** PASS  
**Actual:** Alert shown, item added. Confirmed in cart.  
**End Time:** 10:45

---

### TC_DESK_CAT_15: Verify back navigation from detail to listing  
**Start Time:** 10:46  
**Test Steps:**  
1. Navigate to product detail  
2. Click browser Back button  
**Result:** PASS  
**Actual:** Returned to correct product list page.  
**End Time:** 10:48

---

### TC_DESK_CAT_16: Verify currency consistency across pages  
**Start Time:** 10:49  
**Test Steps:**  
1. Check prices on listing and cart  
**Result:** PASS  
**Actual:** USD symbol consistent on both pages.  
**End Time:** 10:51

---

### TC_DESK_CAT_17: Verify product description text displays correctly  
**Start Time:** 10:52  
**Test Steps:**  
1. Scroll to description area  
2. Read entire paragraph  
**Result:** FAIL  
**Actual:** Text cuts off mid-sentence; word wrapping bug in Firefox.   
**End Time:** 10:55
**Screenshot:**

![Screenshot](/ExecutionResults/Defect_Report_Screenshots/TC_Desk_17_fail.png)

---

### TC_DESK_CAT_18: Verify cart badge persists after page refresh  
**Start Time:** 10:56  
**Test Steps:**  
1. Add item  
2. Refresh browser  
3. Observe cart badge  
**Result:** PASS  
**Actual:** Item count remains after refresh.  
**End Time:** 10:58

---

### TC_DESK_CAT_19: Verify URL changes on category selection  
**Start Time:** 10:59  
**Test Steps:**  
1. Click through categories  
2. Monitor browser address bar  
**Result:** PASS  
**Actual:** URL hash changes match category selected.  
**End Time:** 11:01

---

### TC_DESK_CAT_20: Verify page title updates per category  
**Start Time:** 11:02  
**Test Steps:**  
1. Observe browser tab title after clicking "Laptops"  
**Result:** PASS  
**Actual:** Page title shows "Laptops – DEMOBLAZE".  
**End Time:** 11:04

---

Summary:  
- Total Test Cases: 40  
- Passed: 34  
- Failed: 6 (detailed bug reports linked)  
- Next steps: Retesting of failed cases after bug fixes.
