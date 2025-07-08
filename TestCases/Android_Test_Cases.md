## Android Test Cases – DemoBlaze


### Module: Mobile Android Emulation (Chrome DevTools)

#### TC_MOB_AND_01  
**Title:** Verify hamburger menu toggles visibility  
**Preconditions:** On homepage  
**Test Steps:**  
1. Tap the hamburger menu icon.  
2. Observe menu expansion/collapse.  
**Expected Results:**  
- Menu items show/hide correctly.  
**Priority:** High  
**Type:** Functional  

---

#### TC_MOB_AND_02  
**Title:** Verify category navigation from hamburger menu  
**Preconditions:** Menu expanded  
**Test Steps:**  
1. Tap "Monitors" link.  
**Expected Results:**  
- Navigates to Monitors listing page.  
**Priority:** High  
**Type:** Functional  

---

#### TC_MOB_AND_03  
**Title:** Verify responsive layout on Pixel 5 emulation  
**Preconditions:** On homepage  
**Test Steps:**  
1. Rotate device orientation.  
2. Observe product grid layout.  
**Expected Results:**  
- Grid adjusts columns appropriately for portrait and landscape.  
**Priority:** Medium  
**Type:** UI  

---

#### TC_MOB_AND_04  
**Title:** Verify pagination in Android emulation  
**Preconditions:** On category with >6 items  
**Test Steps:**  
1. Scroll to pagination.  
2. Tap "Next".  
**Expected Results:**  
- Next set of products loads correctly on small viewport.  
**Priority:** Medium  
**Type:** Functional  

---

#### TC_MOB_AND_05  
**Title:** Verify product card layout on Android  
**Preconditions:** On category listing  
**Test Steps:**  
1. Observe first product card.  
**Expected Results:**  
- Image, title, price, and "Add to cart" button are fully visible without overlap.  
**Priority:** Medium  
**Type:** UI  

---

#### TC_MOB_AND_06  
**Title:** Verify "Add to cart" alert on Android  
**Preconditions:** On product listing  
**Test Steps:**  
1. Tap "Add to cart" for an item.  
**Expected Results:**  
- Confirmation alert appears centered and fully visible.  
**Priority:** High  
**Type:** Functional  

---

#### TC_MOB_AND_07  
**Title:** Verify order modal displays correctly
**Preconditions:** Item in cart; cart page open  
**Test Steps:**  
1. Tap "Place Order" button.  
**Expected Results:**  
- Order modal is fully visible and scrollable.  
**Priority:** High  
**Type:** Functional  

---

#### TC_MOB_AND_08  
**Title:** Verify form field alignment in order modal  
**Preconditions:** Order modal open  
**Test Steps:**  
1. Observe all input fields alignment.  
**Expected Results:**  
- Labels and input boxes align correctly without overlap.  
**Priority:** Medium  
**Type:** UI  

---

#### TC_MOB_AND_09  
**Title:** Verify modal scroll behavior on small screens
**Preconditions:** Order modal open  
**Test Steps:**  
1. Swipe up on modal content.  
**Expected Results:**  
- Content scrolls smoothly; bottom fields accessible.  
**Priority:** Medium  
**Type:** Functional  

---

#### TC_MOB_AND_10  
**Title:** Verify responsive page title visibility
**Preconditions:** On any page  
**Test Steps:**  
1. Check document title in tab UI on emulation.  
**Expected Results:**  
- Title text is legible and not truncated.  
**Priority:** Low  
**Type:** UI  

---