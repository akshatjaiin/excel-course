# Excel Conditionals Cheat Sheet

A quick reference for using **IF**, **NOT**, **AND**, **OR**, **COUNTIF**, and more in Excel. Syntax-highlighted for clarity.

---

## ✅ Basic Conditional Functions

### IF  
=IF(logical_test, value_if_true, value_if_false)  
**Example:**  
=IF(A1>10, "High", "Low")

---

### AND  
=AND(condition1, condition2, ...)  
**Example:**  
=IF(AND(A1>10, B1<5), "Yes", "No")

---

### OR  
=OR(condition1, condition2, ...)  
**Example:**  
=IF(OR(A1="Yes", B1="Yes"), "Accepted", "Denied")

---

### NOT  
=NOT(condition)  
**Example:**  
=IF(NOT(A1=10), "Not Ten", "Ten")

---

## 🔢 COUNT & SUM with Conditions

### COUNTIF  
=COUNTIF(range, criteria)  
**Example:**  
=COUNTIF(A1:A10, ">10")

---

### COUNTIFS *(Multiple Criteria)*  
=COUNTIFS(range1, criteria1, range2, criteria2, ...)  
**Example:**  
=COUNTIFS(A1:A10, ">10", B1:B10, "<5")

---

### SUMIF  
=SUMIF(range, criteria, sum_range)  
**Example:**  
=SUMIF(A1:A10, ">10", B1:B10)

---

### SUMIFS *(Multiple Criteria)*  
=SUMIFS(sum_range, range1, criteria1, range2, criteria2, ...)  
**Example:**  
=SUMIFS(B1:B10, A1:A10, ">10", C1:C10, "<5")

---

## ✨ Nested IF (Multiple Conditions)

=IF(A1>90, "A", IF(A1>80, "B", IF(A1>70, "C", "F")))

---

## 🟡 Text Comparisons

=IF(A1="apple", "Fruit", "Not Fruit")  
Use double quotes for **text strings** in Excel.

---

## ⚠️ Tips

- Use "" for blank:  
  =IF(A1="", "Empty", "Filled")

- Combine with ISBLANK:  
  =IF(ISBLANK(A1), "Missing", A1)

- Use <> for "not equal":  
  =IF(A1<>10, "Not 10", "Yes 10")

---

**Made with love for spreadsheet wizards.**
