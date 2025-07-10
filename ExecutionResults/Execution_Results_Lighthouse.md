# Performance Audit Results – DemoBlaze

**Date:** 10.07.2025  
**Auditor:** Aleksa Aleksić

---

## Summary Table

| Page             | Device   | FCP   | Speed Index | TTI   | TBT   | LCP   | CLS   |
|------------------|----------|-------|-------------|-------|-------|-------|-------|
| Home             | Desktop  | 1.1s  | 1.9s        | 2.4s  | 100ms | 1.5s  | 0.01  |
| Home             | Mobile   | 1.6s  | 3.2s        | 4.0s  | 250ms | 2.1s  | 0.04  |
| Product Detail   | Desktop  | 1.0s  | 2.0s        | 2.6s  | 110ms | 1.6s  | 0.02  |
| Product Detail   | Mobile   | 1.5s  | 3.0s        | 3.8s  | 260ms | 2.3s  | 0.05  |
| Cart             | Desktop  | 1.2s  | 2.2s        | 2.9s  | 130ms | 1.7s  | 0.03  |
| Cart             | Mobile   | 1.9s  | 3.5s        | 4.3s  | 300ms | 2.5s  | 0.06  |

---

## Detailed Findings

### Home – Desktop
- **First Contentful Paint (FCP):** 1.1s – Exceeds target (<2s).
- **Speed Index:** 1.9s – Excellent (<2s).
- **Time to Interactive (TTI):** 2.4s – Meets goal (<2.5s).
- **Total Blocking Time (TBT):** 100ms – Low blocking.
- **Largest Contentful Paint (LCP):** 1.5s – Good (<2.5s).
- **Cumulative Layout Shift (CLS):** 0.01 – Very stable.  
**Opportunities:**
  - Compress hero banner image (`banner.jpg`) by 30%.
  - Defer non-critical JS (`analytics.js`).

---

### Home – Mobile
- **FCP:** 1.6s – Good (<2s).
- **Speed Index:** 3.2s – Slightly above ideal (≤3s).
- **TTI:** 4.0s – Acceptable (<4.5s).
- **TBT:** 250ms – Moderate blocking; reduce JS execution.
- **LCP:** 2.1s – Good (<2.5s).
- **CLS:** 0.04 – Minor shifts; optimize font loading.  
**Opportunities:**
  - Use adaptive image formats (WebP) for mobile.
  - Minimize render-blocking CSS.

---

### Product Detail – Desktop
- **FCP:** 1.0s – Excellent.
- **Speed Index:** 2.0s – Excellent.
- **TTI:** 2.6s – On target.
- **TBT:** 110ms – Low.
- **LCP:** 1.6s – Good.
- **CLS:** 0.02 – Stable.  
**Opportunities:**
  - Lazy-load product images below the fold.
  - Inline critical CSS for above-the-fold content.

---

### Product Detail – Mobile
- **FCP:** 1.5s – Good.
- **Speed Index:** 3.0s – Meets expectations.
- **TTI:** 3.8s – Acceptable.
- **TBT:** 260ms – Moderate.
- **LCP:** 2.3s – Good.
- **CLS:** 0.05 – Slight layout shifts on image load.  
**Opportunities:**
  - Preconnect to font servers.
  - Reduce JavaScript payloads for mobile.

---

### Cart – Desktop
- **FCP:** 1.2s – Good.
- **Speed Index:** 2.2s – Good.
- **TTI:** 2.9s – Meets goal.
- **TBT:** 130ms – Low.
- **LCP:** 1.7s – Good.
- **CLS:** 0.03 – Minor shifts around total calculation.  
**Opportunities:**
  - Optimize cart icon SVG rendering.
  - Combine cart summary scripts.

---

### Cart – Mobile
- **FCP:** 1.9s – Acceptable.
- **Speed Index:** 3.5s – Slightly high.
- **TTI:** 4.3s – Acceptable.
- **TBT:** 300ms – Consider reducing JS.
- **LCP:** 2.5s – On threshold.
- **CLS:** 0.06 – Slight shifts; optimize layout.  
**Opportunities:**
  - Defer less-critical widgets in cart (e.g., recommendations).
  - Enable text compression (Brotli).

---

## Artifacts

- [Lighthouse_Home_Desktop.html](../Reports/Lighthouse_Reports/Lighthouse_Home_Desktop.html)  
- [Lighthouse_Home_Mobile.html](../Reports/Lighthouse_Reports/Lighthouse_Home_Mobile.html)  
- [Lighthouse_ProductDetail_Desktop.html](../Reports/Lighthouse_Reports/Lighthouse_ProductDetail_Desktop.html)  
- [Lighthouse_ProductDetail_Mobile.html](../Reports/Lighthouse_Reports/Lighthouse_ProductDetail_Mobile.html)  
- [Lighthouse_Cart_Desktop.html](../Reports/Lighthouse_Reports/Lighthouse_Cart_Desktop.html)  
- [Lighthouse_Cart_Mobile.html](../Reports/Lighthouse_Reports/Lighthouse_Cart_Mobile.html)  

