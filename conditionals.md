# 🎀 Excel Conditionals Cheat Sheet 🎀  
_The guide to Excel logic magic ✨📊_

---

![Excel Cute](https://media.giphy.com/media/5GoVLqeAOo6PK/giphy.gif)

## ✅ Basic Conditional Spells

### 🧠 `IF`  
```excel
=IF(logical_test, value_if_true, value_if_false)
```
💡 _If something is true, do this, otherwise do that._

**Example:**  
```excel
=IF(A1>10, "High 📈", "Low 📉")
```

---

### 🤝 `AND`  
```excel
=AND(condition1, condition2, ...)
```
💡 _All must be true or it won’t work!_

**Example:**  
```excel
=IF(AND(A1>10, B1<5), "Yes ✅", "No ❌")
```

---

### 🔀 `OR`  
```excel
=OR(condition1, condition2, ...)
```
💡 _Only one needs to be true!_

**Example:**  
```excel
=IF(OR(A1="Yes", B1="Yes"), "Accepted 💌", "Denied 🚫")
```

---

### ❌ `NOT`  
```excel
=NOT(condition)
```
💡 _Flips true ➡ false, false ➡ true_

**Example:**  
```excel
=IF(NOT(A1=10), "Not Ten 🙅‍♀️", "Ten 🙆‍♂️")
```

---

## 🔢 Counting & Summing Spells

### 🔍 `COUNTIF`  
```excel
=COUNTIF(range, criteria)
```
💡 _Count cells with one condition_

**Example:**  
```excel
=COUNTIF(A1:A10, ">10")
```

---

### 🧮 `COUNTIFS`  
```excel
=COUNTIFS(range1, criteria1, range2, criteria2)
```
💡 _Count with multiple conditions_

**Example:**  
```excel
=COUNTIFS(A1:A10, ">10", B1:B10, "<5")
```

---

### 💰 `SUMIF`  
```excel
=SUMIF(range, criteria, sum_range)
```
💡 _Add numbers if condition is met_

**Example:**  
```excel
=SUMIF(A1:A10, ">10", B1:B10)
```

---

### 🧙‍♀️ `SUMIFS`  
```excel
=SUMIFS(sum_range, range1, criteria1, ...)
```
💡 _Multiple condition summing!_

**Example:**  
```excel
=SUMIFS(B1:B10, A1:A10, ">10", C1:C10, "<5")
```

---

## 🔁 Nested `IF` (Multiverse of Maybes)

```excel
=IF(A1>90, "A", IF(A1>80, "B", IF(A1>70, "C", "F")))
```
💡 _Like Russian dolls of logic... 🎎_

---

## 🟡 Text Match Spells

```excel
=IF(A1="apple", "Fruit 🍎", "Not Fruit 😬")
```
💡 _Use double quotes for words!_

---

## ⚠️ Magical Tips

- Empty check:  
```excel
=IF(A1="", "Empty 🕳️", "Filled 💖")
```

- Is blank:  
```excel
=IF(ISBLANK(A1), "Missing 🔍", A1)
```

- Not equal:  
```excel
=IF(A1<>10, "Not 10 🙅", "Yes 10 ✅")
```

---

![Sparkly Excel](https://media.giphy.com/media/YT8qB3xG4b2w/giphy.gif)

---

**Made with love 💗 for spreadsheet wizards ✨🧙**  
