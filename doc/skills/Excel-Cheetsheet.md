<div align="center">
  <br>
  <h1>📊 Excel Formula Cheat Sheet 📊</h1>
  <br>
  <p>A community-driven collection of powerful Excel formulas and solutions for common problems.<br>Click on any formula to expand and see the details.</p>
</div>

<div align="center">
  <a href="#"><img src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white"></a>
  <a href="#"><img src="https://img.shields.io/badge/Status-In_Progress-yellow?style=for-the-badge"></a>
  <a href="#-how-to-contribute"><img src="https://img.shields.io/badge/Contributions-Welcome-brightgreen?style=for-the-badge"></a>
</div>

---

## 🧭 Table of Contents

* [Text Formulas](#-text-formulas)
* [Lookup Formulas](#-lookup-formulas)
* [Logical Formulas](#-logical-formulas)

---

## ✍️ Text Formulas

Formulas used for manipulating, joining, or splitting text strings.

<details>
<summary>
  <strong>➡️ Combine Text from Many Cells (TEXTJOIN)</strong>
  <br>
  <small>Joins a list of items into a single cell with a custom separator.</small>
</summary>
<br>

> **Problem:** I have a list of items (e.g., in cells `A1` to `A90`) and I want to join them all into a *single cell*, separated by a comma and space.
>
> **Solution:** Use the `TEXTJOIN` formula.

#### **Formula:**

```excel
=TEXTJOIN(", ", TRUE, A1:A90)
```

### **How it Works:**

* =**TEXTJOIN(** : The name of the formula.
* **", "** (in quotes): This is the delimiter. It's the text that will be placed between each item.
* **TRUE**: This tells Excel to ignore any empty cells in your range. (Use FALSE if you want to include blanks).
* **A1:A90** : This is the range of cells you want to combine.

> **Note:** [Add any extra tips, warnings, or "gotchas" here.]

### **Excel-Contributions:**

<details> 
  <summary> 
  <strong>➡️ Click to copy the Excel Formula Template</strong> 
  </summary>
  
Note: Copy the code block below to add a new Excel formula to the main Excel-formulas.md.


> **Problem:** [A short description of the problem you are solving.]
>
> **Solution:** [Name the formula you are using, e.g., `TEXTSPLIT`.]

#### **Formula:**

` ``excel
[Your Formula Here, e.g., =TEXTSPLIT(A1, "-")]
` ``

#### **How it Works:**

* `[Part 1]`: [Explanation of the first part]
* `[Part 2]`: [Explanation of the second part]

> **Note:** [Add any extra tips, warnings, or "gotchas" here.]

</details>
