## Desktop Test Cases – DemoBlaze

### Module: Product Categories (Navigation)

#### TC_DESK_CAT_01  
**Title:** Verify navigation to "Phones" category  
**Preconditions:** On homepage  
**Test Steps:**  
1. Click on the "Phones" category link.  
**Expected Results:**  
- The page displays only phone products.  
**Priority:** High  
**Type:** Functional  

---

#### TC_DESK_CAT_02  
**Title:** Verify navigation to "Laptops" category  
**Preconditions:** On homepage  
**Test Steps:**  
1. Click on the "Laptops" category link.  
**Expected Results:**  
- The page displays only laptop products.  
**Priority:** High  
**Type:** Functional  

---

#### TC_DESK_CAT_03  
**Title:** Verify navigation to "Monitors" category  
**Preconditions:** On homepage  
**Test Steps:**  
1. Click on the "Monitors" category link.  
**Expected Results:**  
- The page displays only monitor products.  
**Priority:** High  
**Type:** Functional  

---

### Module: Product Categories (Pagination)

#### TC_DESK_CAT_04  
**Title:** Verify pagination next page  
**Preconditions:** On any category with more than 6 items  
**Test Steps:**  
1. Click the "Next" pagination button at bottom of the page.  
**Expected Results:**  
- The next set of products is loaded and displayed.  
**Priority:** Medium  
**Type:** Functional  

---

#### TC_DESK_CAT_05  
**Title:** Verify pagination previous page  
**Preconditions:** On second page of a category listing  
**Test Steps:**  
1. Click the "Previous" pagination button.  
**Expected Results:**  
- The first set of products is displayed.  
**Priority:** Medium  
**Type:** Functional  

---

#### TC_DESK_CAT_06  
**Title:** Verify pagination buttons disabled state  
**Preconditions:** On first page of category  
**Test Steps:**  
1. Observe "Previous" button state.  
2. Navigate to last page.  
3. Observe "Next" button state.  
**Expected Results:**  
- "Previous" is disabled on first page; "Next" disabled on last page.  
**Priority:** Low  
**Type:** UI  

---

### Module: Add-to-Cart

#### TC_DESK_CAT_07  
**Title:** Verify adding a phone to cart from category listing  
**Preconditions:** On "Phones" category  
**Test Steps:**  
1. Click "Add to cart" under first phone item.  
**Expected Results:**  
- Alert confirms product added.  
- Cart badge increments by 1.  
**Priority:** High  
**Type:** Functional  

---

#### TC_DESK_CAT_08  
**Title:** Verify adding a laptop to cart from category listing  
**Preconditions:** On "Laptops" category  
**Test Steps:**  
1. Click "Add to cart" under first laptop item.  
**Expected Results:**  
- Alert confirms product added.  
- Cart badge increments by 1.  
**Priority:** High  
**Type:** Functional  

---

#### TC_DESK_CAT_09  
**Title:** Verify adding multiple items from different categories  
**Preconditions:** On homepage  
**Test Steps:**  
1. Add one phone.  
2. Navigate to "Laptops", add one laptop.  
3. Navigate to "Monitors", add one monitor.  
**Expected Results:**  
- Cart badge shows total count = 3.  
**Priority:** High  
**Type:** Functional  

---

#### TC_DESK_CAT_10  
**Title:** Verify removing item from cart badge via category listing  
**Preconditions:** Item already in cart  
**Test Steps:**  
1. Click "Add to cart" to add one item.  
2. Open cart and remove the item.  
3. Return to category listing.  
**Expected Results:**  
- Cart badge decrements to 0.  
**Priority:** Medium  
**Type:** Functional  

---

### Module: Product Detail View

#### TC_DESK_CAT_11  
**Title:** Verify product detail displays correct name  
**Preconditions:** On any category listing  
**Test Steps:**  
1. Click on first product title.  
**Expected Results:**  
- Detail page shows product name matching listing.  
**Priority:** High  
**Type:** Functional  

---

#### TC_DESK_CAT_12  
**Title:** Verify product detail displays correct price  
**Preconditions:** On product detail page  
**Test Steps:**  
1. Compare price on detail page with listing.  
**Expected Results:**  
- Prices match exactly.  
**Priority:** High  
**Type:** Functional  

---

#### TC_DESK_CAT_13  
**Title:** Verify product images load properly  
**Preconditions:** On product detail page  
**Test Steps:**  
1. Observe product image.  
**Expected Results:**  
- Image is displayed without distortion or placeholder.  
**Priority:** Medium  
**Type:** UI  

---

#### TC_DESK_CAT_14  
**Title:** Verify "Add to cart" from product detail page  
**Preconditions:** On product detail page  
**Test Steps:**  
1. Click "Add to cart" button.  
**Expected Results:**  
- Alert confirms addition.  
- Cart badge increments by 1.  
**Priority:** High  
**Type:** Functional  

---

#### TC_DESK_CAT_15  
**Title:** Verify back navigation from detail to listing  
**Preconditions:** On product detail page  
**Test Steps:**  
1. Click browser Back button.  
**Expected Results:**  
- Returns to previous category listing.  
**Priority:** Medium  
**Type:** Functional  

---

### Additional Desktop Cases

#### TC_DESK_CAT_16  
**Title:** Verify currency consistency across pages  
**Preconditions:** On any page  
**Test Steps:**  
1. Note currency symbol on homepage and detail pages.  
**Expected Results:**  
- Currency symbol is the same (e.g., $) throughout.  
**Priority:** Low  
**Type:** UI  

---

#### TC_DESK_CAT_17  
**Title:** Verify product description text displays correctly  
**Preconditions:** On product detail page  
**Test Steps:**  
1. Read description text for special characters or truncation.  
**Expected Results:**  
- Description is complete, no broken lines.  
**Priority:** Low  
**Type:** UI  

---

#### TC_DESK_CAT_18  
**Title:** Verify cart badge persists after page refresh  
**Preconditions:** Item in cart  
**Test Steps:**  
1. Refresh browser.  
**Expected Results:**  
- Cart badge count remains unchanged.  
**Priority:** Medium  
**Type:** Functional  

---

#### TC_DESK_CAT_19  
**Title:** Verify URL changes on category selection  
**Preconditions:** On homepage  
**Test Steps:**  
1. Click "Laptops" category.  
**Expected Results:**  
- URL contains query or path indicating selected category.  
**Priority:** Low  
**Type:** UI  

---

#### TC_DESK_CAT_20  
**Title:** Verify page title updates per category  
**Preconditions:** On homepage  
**Test Steps:**  
1. Select each category.  
2. Observe document title in browser tab.  
**Expected Results:**  
- Title reflects category name, e.g., "Products - Laptops".  
**Priority:** Low  
**Type:** UI  

---