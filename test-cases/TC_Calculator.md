# Test Cases - Calculator App
**Application:** Default Calculator (Mobile)
**Tested by:** Rithu
**Date:** 3 june 2026
**Test Technique used:**  Equivalence Partitioning, Boundary Value Analysis

---
## 1. Basic Operations
| TC ID | Test Case Title | Steps | Expected Result | Status |
|---|---|---|---|---|
| TC_001 | Addition | Enter 5+3= | Result: 8 | Not Run |
| TC_002 | Subtraction | Enter 10-4= |Result: 6 | Not Run |
| TC_003 | Multiplication | Enter 6*7= | Result: 42 | Not Run |
| TC_004 | Division | Enter 20/4= | Result: 5 | Not Run |

---
## 2. Edge Cases
| TC ID | Test Case Title | Steps | Expected Result | Status |
|---|---|---|---|---|
| TC_005 | Divide by zero | Enter 10/0= | Error message displayed eg. "Cannot divide by zero" | Not Run |
| TC_006 | Decimal result | Enter 10/3= | Result: 3.3333... (rounded appropriately) | Not Run |
| TC_007 | Negative result | Enter 3-10= | Result: -7 | Not Run |
| TC_008 | Multiply by zero | Enter 999*0= | Result: 0 | Not Run |
| TC_009 | Multiply by negative | Enter 5*-3= | Result: -15 | Not Run |

---
## 3. Boundary Value Analysis
| TC ID | Test Case Title | Steps | Expected Result | Status |
|---|---|---|---|---|
| TC_010 | Very large numbers | Enter 999999999+1= | Result handled without crash or overflow error | Not Run |
| TC_011 | Very small decimal | Enter 0.0001+0.0001= | Result: 0.0002 (no rounding error) | Not Run |
| TC_012 | zero+zero | Enter 0+0= | Result: 0 | Not Run |
| TC_013 | Negative+Negative | Enter -5+-5= | Result: -10 | Not Run |

---

## 4. UI & Functional Checks
| TC ID | Test Case Title | Steps | Expected Result | Status |
|---|---|---|---|---|
| TC_014 | Clear button | Enter any number, press C | Display resets to 0 | Not Run |
| TC_015 | Consecutive operations | Enter 2+3=then*4= | Result: 20 | Not Run |
| TC_016 | Repeated equals | Enter 5+3=then press = again | Result rpeats last operation (shows 11) | Not Run |
| TC_017 | Display limit | Enter a very long number eg. 123456789012345 | Display adjusts without breaking layout | Not Run |

---

