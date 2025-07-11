# Bug Retest Results – 11-07-2025

## Retest Execution Summary
Re-tested all previously logged bugs in Chrome 138.0.7204.92 and Mozilla 140.0.4 on Ubuntu 22.04 LTS (DevTools emulation for mobile).  

---

### Bug ID: TC_DESK_CAT_03  
- **Retested in Mozilla 140.0.4**  
- **Status:** Still Reproducible  
- **Comment:** Monitors category still fails to load; console error persists (`TypeError: undefined is not iterable`).  

---

### Bug ID: TC_DESK_CAT_07  
- **Retested in Mozilla 140.0.4**  
- **Status:** Still Reproducible  
- **Comment:** "Add to cart" does not trigger alert or increment badge; no change in behavior.  

---

### Bug ID: TC_DESK_CAT_10  
- **Retested in Chrome 138.0.7204.92**  
- **Status:** Still Reproducible  
- **Comment:** Cart badge remains at 1 after removal of item; UI update not fixed.  

---

### Bug ID: TC_DESK_CAT_17  
- **Retested in Mozilla 140.0.4**  
- **Status:** Still Reproducible  
- **Comment:** Product description text still truncated mid-sentence in Firefox/Chrome.  

---

### Bug ID: TC_DESK_CAT_18  
- **Retested in Chrome 138.0.7204.92**  
- **Status:** Still Reproducible  
- **Comment:** Badge resets to 0 on refresh; session persistence bug remains.  

---

### Bug ID: TC_DESK_CAT_20  
- **Retested in Chrome 138.0.7204.92**  
- **Status:** Fixed  
- **Comment:** Page title now updates correctly to reflect selected category.  

---

### Bug ID: TC_MOB_iOS_03  
- **Retested in Chrome 138.0.7204.92 (iOS Emulation)**  
- **Status:** Still Reproducible  
- **Comment:** Grid overlap persists in landscape orientation on iPhone X emulation.  

---

### Bug ID: TC_MOB_iOS_08  
- **Retested in Chrome 138.0.7204.92 (iOS Emulation)**  
- **Status:** Fixed  
- **Comment:** Form labels and inputs now align correctly in the order modal.  

---

### Bug ID: TC_MOB_AND_03  
- **Retested in Chrome 138.0.7204.92 (Android Emulation)**  
- **Status:** Still Reproducible  
- **Comment:** Grid misalignment in landscape view remains on Pixel 5 emulation.  

---

### Bug ID: TC_MOB_AND_08  
- **Retested in Chrome 138.0.7204.92 (Android Emulation)**  
- **Status:** Fixed  
- **Comment:** Field labels now align properly with inputs in Android order modal.  

---
