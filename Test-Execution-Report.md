# 📄 Test Execution Report
**Project:** E-Commerce Website – Manual Testing  
**Tester:** Ananya Vashisht  
**Test Cycle:** Cycle 1  
**Execution Status:** Completed  

---

## 🧪 Test Summary

| Metric | Count |
|--------|-------|
| **Total Test Cases Executed** | 60 |
| **Passed** | 56 |
| **Failed** | 4 |
| **Blocked** | 0 |
| **Defects Logged** | 4 |
| **Execution Coverage** | 100% |

---

## 🗂 Module-wise Execution Status

| Module | Total TCs | Passed | Failed | Blocked | Defects Logged |
|--------|------------|---------|---------|----------|----------------|
| Login | 6 | 5 | 1 | 0 | BUG-LG-01 |
| Register | 8 | 7 | 1 | 0 | BUG-RG-01 |
| Homepage | 5 | 5 | 0 | 0 | — |
| Search | 8 | 8 | 0 | 0 | — |
| Product Listing Page (PLP) | 5 | 5 | 0 | 0 | — |
| Product Details Page (PDP) | 5 | 5 | 0 | 0 | — |
| Cart | 5 | 5 | 0 | 0 | — |
| Wishlist | 5 | 5 | 0 | 0 | — |
| Checkout | 5 | 5 | 0 | 0 | — |
| Order Confirmation | 4 | 2 | 2 | 0 | BUG-OC-01, BUG-OC-02 |
| Order History | 4 | 4 | 0 | 0 | — |

---

## 🐞 Defects Logged During Execution

| Defect ID | Module | Severity | Status | Description |
|-----------|---------|----------|---------|-------------|
| **BUG-LG-01** | Login | Medium | Open | Wrong error message for empty email |
| **BUG-RG-01** | Register | Medium | Open | Wrong validation message for missing required field |
| **BUG-OC-01** | Order Confirmation | High | Open | Order confirmation page missing |
| **BUG-OC-02** | Order Confirmation | Medium | Open | Order summary missing |

---

## 📌 Observations

- Core flows function correctly across major modules.  
- Order Confirmation module contains major defects impacting user experience.  
- Validation logic on Login and Register requires improvement.  
- No UI alignment or performance issues were observed.

---

## ✅ Conclusion

The application is generally stable, with **4 failed test cases** corresponding to valid defects.  
A retest cycle is recommended once fixes are applied.
