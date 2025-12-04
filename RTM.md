# 📄 Requirements Traceability Matrix (RTM)

This matrix maps User Flows → Test Scenarios → Test Cases → Status → Defects Logged.

---

## 🔹 Login Module
| User Flow | Scenario ID | Test Case ID | Status | Defect ID |
|-----------|-------------|---------------|--------|-----------|
| Valid Login | TS-LG-01 | TC-LG-01 | Pass | — |
| Invalid Password | TS-LG-02 | TC-LG-02 | Pass | — |
| Unregistered Email | TS-LG-03 | TC-LG-03 | Pass | — |
| Partial Input | TS-LG-04 | TC-LG-04 | **Fail** | **BUG-LG-01** |
| Invalid Email Format | TS-LG-05 | TC-LG-05 | Pass | — |
| Post-login Redirection | TS-LG-09 | TC-LG-06 | Pass | — |

---

## 🔹 Register Module
| User Flow | Scenario ID | Test Case ID | Status | Defect ID |
|-----------|-------------|---------------|--------|-----------|
| Valid Registration | TS-RG-01 | TC-RG-01 | Pass | — |
| Existing Email | TS-RG-02 | TC-RG-02 | Pass | — |
| Empty Mandatory Fields | TS-RG-03 | TC-RG-03 | **Fail** | **BUG-RG-01** |
| Invalid Email Format | TS-RG-04 | TC-RG-04 | Pass | — |
| Password Mismatch | TS-RG-05 | TC-RG-05 | Pass | — |
| Privacy Policy Not Selected | TS-RG-06 | TC-RG-06 | Pass | — |
| Newsletter Optional | TS-RG-07 | TC-RG-07 | Pass | — |
| Redirection After Registration | TS-RG-08 | TC-RG-08 | Pass | — |

---

## 🔹 Homepage Module
| User Flow | Scenario ID | Test Case ID | Status | Defect ID |
|-----------|-------------|---------------|--------|-----------|
| Homepage Load | TS-HP-01 | TC-HP-01 | Pass | — |
| Header Navigation | TS-HP-02 | TC-HP-02 | Pass | — |
| Search Bar Access | TS-HP-03 | TC-HP-03 | Pass | — |
| Featured Product Click | TS-HP-04 | TC-HP-04 | Pass | — |
| Banner/Slider Click | TS-HP-05 | TC-HP-05 | Pass | — |

---

## 🔹 Search Module
| User Flow | Scenario ID | Test Case ID | Status | Defect ID |
|-----------|-------------|---------------|--------|-----------|
| Valid Search | TS-SR-01 | TC-SR-01 | Pass | — |
| Partial Keyword | TS-SR-02 | TC-SR-02 | Pass | — |
| No Results | TS-SR-03 | TC-SR-03 | Pass | — |
| Empty Search | TS-SR-04 | TC-SR-04 | Pass | — |
| Special Characters | TS-SR-05 | TC-SR-05 | Pass | — |
| Case Insensitive Search | TS-SR-06 | TC-SR-06 | Pass | — |
| Quick Search | TS-SR-07 | TC-SR-07 | Pass | — |
| Product Click From Results | TS-SR-08 | TC-SR-08 | Pass | — |

---

## 🔹 Product Listing Page (PLP)
| User Flow | Scenario ID | Test Case ID | Status | Defect ID |
|-----------|-------------|---------------|--------|-----------|
| PLP Load | TS-PLP-01 | TC-PLP-01 | Pass | — |
| Open Product | TS-PLP-03 | TC-PLP-02 | Pass | — |
| Add to Cart from PLP | TS-PLP-04 | TC-PLP-03 | Pass | — |
| Sorting | TS-PLP-05 | TC-PLP-04 | Pass | — |
| No Products | TS-PLP-06 | TC-PLP-05 | Pass | — |

---

## 🔹 Product Details Page (PDP)
| User Flow | Scenario ID | Test Case ID | Status | Defect ID |
|-----------|-------------|---------------|--------|-----------|
| PDP Load | TS-PDP-01 | TC-PDP-01 | Pass | — |
| Add to Cart | TS-PDP-03 | TC-PDP-02 | Pass | — |
| Quantity Selection | TS-PDP-04 | TC-PDP-03 | Pass | — |
| Image Preview | TS-PDP-05 | TC-PDP-04 | Pass | — |
| Back to PLP | TS-PDP-06 | TC-PDP-05 | Pass | — |

---

## 🔹 Cart Module
| User Flow | Scenario ID | Test Case ID | Status | Defect ID |
|-----------|-------------|---------------|--------|-----------|
| Add to Cart | TS-CT-01 | TC-CT-01 | Pass | — |
| Update Quantity | TS-CT-02 | TC-CT-02 | Pass | — |
| Remove Item | TS-CT-04 | TC-CT-03 | Pass | — |
| Cart Persistence | TS-CT-06 | TC-CT-04 | Pass | — |
| Proceed to Checkout | TS-CT-08 | TC-CT-05 | Pass | — |

---

## 🔹 Wishlist Module
| User Flow | Scenario ID | Test Case ID | Status | Defect ID |
|-----------|-------------|---------------|--------|-----------|
| Add to Wishlist | TS-WL-01 | TC-WL-01 | Pass | — |
| Login Requirement | TS-WL-02 | TC-WL-02 | Pass | — |
| View Wishlist | TS-WL-03 | TC-WL-03 | Pass | — |
| Remove From Wishlist | TS-WL-04 | TC-WL-04 | Pass | — |
| Move to Cart | TS-WL-05 | TC-WL-05 | Pass | — |

---

## 🔹 Checkout Module
| User Flow | Scenario ID | Test Case ID | Status | Defect ID |
|-----------|-------------|---------------|--------|-----------|
| Checkout Page Load | TS-CK-01 | TC-CK-01 | Pass | — |
| Guest/Registered Flow | TS-CK-02 | TC-CK-02 | Pass | — |
| Billing & Delivery | TS-CK-04 | TC-CK-03 | Pass | — |
| Payment Selection | TS-CK-06 | TC-CK-04 | Pass | — |
| Confirm Order Navigation | TS-CK-07 | TC-CK-05 | Pass | — |

---

## 🔹 Order Confirmation Module
| User Flow | Scenario ID | Test Case ID | Status | Defect ID |
|-----------|-------------|---------------|--------|-----------|
| Confirmation Page Load | TS-OC-01 | TC-OC-01 | **Fail** | **BUG-OC-01** |
| Order Summary | TS-OC-02 | TC-OC-02 | **Fail** | **BUG-OC-02** |
| Success Message | TS-OC-03 | TC-OC-03 | Pass | — |
| Navigate to Order History | TS-OC-04 | TC-OC-04 | Pass | — |

---

## 🔹 Order History Module
| User Flow | Scenario ID | Test Case ID | Status | Defect ID |
|-----------|-------------|---------------|--------|-----------|
| Order History Load | TS-OH-01 | TC-OH-01 | Pass | — |
| View Order Details | TS-OH-02 | TC-OH-02 | Pass | — |
| Reorder | TS-OH-04 | TC-OH-03 | Pass | — |
| No Orders | TS-OH-05 | TC-OH-04 | Pass | — |
