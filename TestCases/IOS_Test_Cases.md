## iOS Test Cases – DemoBlaze


### Module: Mobile iOS Emulation (Chrome DevTools)

#### TC_MOB_iOS_01  
**Title:** Verify hamburger menu toggles visibility  
**Preconditions:** On homepage  
**Test Steps:**  
1. Tap the hamburger menu icon.  
2. Observe menu expansion.  
3. Tap the icon again.  
**Expected Results:**  
- Menu items appear when expanded; menu hides when collapsed.  
**Priority:** High  
**Type:** Functional  

---

#### TC_MOB_iOS_02  
**Title:** Verify category links accessible in hamburger menu  
**Preconditions:** Menu expanded  
**Test Steps:**  
1. Expand hamburger menu.  
2. Tap "Laptops" link.  
**Expected Results:**  
- Navigates to Laptops listing page.  
**Priority:** High  
**Type:** Functional  

---

#### TC_MOB_iOS_03  
**Title:** Verify responsive grid on homepage  
**Preconditions:** On homepage  
**Test Steps:**  
1. Rotate device orientation.  
2. Observe product grid layout.  
**Expected Results:**  
- Grid adjusts columns appropriately for portrait and landscape.  
**Priority:** Medium  
**Type:** UI  

---

#### TC_MOB_iOS_04  
**Title:** Verify pagination buttons in mobile view  
**Preconditions:** On category with >6 items  
**Test Steps:**  
1. Scroll to pagination.  
2. Tap "Next".  
**Expected Results:**  
- Next set of products loads correctly on small viewport.  
**Priority:** Medium  
**Type:** Functional  

---

#### TC_MOB_iOS_05  
**Title:** Verify product card layout on iPhone X emulation  
**Preconditions:** On category listing  
**Test Steps:**  
1. Observe first product card.  
**Expected Results:**  
- Image, title, price, and "Add to cart" button are fully visible without overlap.  
**Priority:** Medium  
**Type:** UI  

---

#### TC_MOB_iOS_06  
**Title:** Verify "Add to cart" alert positioning
**Preconditions:** On product listing  
**Test Steps:**  
1. Tap "Add to cart" for an item.  
**Expected Results:**  
- Confirmation alert appears centered and fully visible.  
**Priority:** High  
**Type:** Functional  

---

#### TC_MOB_iOS_07  
**Title:** Verify order modal displays correctly
**Preconditions:** Item in cart; cart page open  
**Test Steps:**  
1. Tap "Place Order" button.  
**Expected Results:**  
- Order modal is fully visible and scrollable.  
**Priority:** High  
**Type:** Functional  

---

#### TC_MOB_iOS_08  
**Title:** Verify form field alignment in order modal  
**Preconditions:** Order modal open  
**Test Steps:**  
1. Observe all input fields alignment.  
**Expected Results:**  
- Labels and input boxes align correctly without overlap.  
**Priority:** Medium  
**Type:** UI  

---

#### TC_MOB_iOS_09  
**Title:** Verify modal scroll behavior on small screens
**Preconditions:** Order modal open  
**Test Steps:**  
1. Swipe up on modal content.  
**Expected Results:**  
- Content scrolls smoothly; bottom fields accessible.  
**Priority:** Medium  
**Type:** Functional  

---

#### TC_MOB_iOS_10  
**Title:** Verify responsive page title visibility
**Preconditions:** On any page  
**Test Steps:**  
1. Check document title in tab UI on emulation.  
**Expected Results:**  
- Title text is legible and not truncated.  
**Priority:** Low  
**Type:** UI  

---
