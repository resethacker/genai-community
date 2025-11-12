<div align="center">
  <br>
  <h1>📈 Contribution Template Bank</h1>
  <br>
  <p>This file contains all the blank templates used to add new cheat sheet items, as well as the LLM prompt to automate formatting.<br>Click on any section to expand and see the details.</p>
</div>

---

## 🧭 Table of Contents
* [LLM Prompt](#-llm-prompt-note-for-yourself)
* [Excel Contributions](#-excel-contributions)
* [PowerPoint Contributions](#-microsoft-ppt-contributions)

---

## 🤖 LLM Prompt (Note for Yourself)

<details>
<summary>
  <strong>➡️ Click to expand the LLM Prompt Template</strong>
</summary>
<br>

> Here is the note you can save to use with an LLM. It's a "master prompt" that instructs the AI to find the right template from a provided list.

```text
You are an AI assistant helping me manage my GitHub cheat sheet.

My central template bank is stored in a file named `CONTRIBUTING.md`. I will provide you with the content of that file first. Then, I will give you my raw notes.

Your job is to:
1.  Read the `CONTRIBUTING.md` content I provide to see all available templates.
2.  Analyze my raw notes and identify which tool they are for (e.g., "Excel", "Jira").
3.  Find the correct blank template for that tool from the `CONTRIBUTING.md` content.
4.  Use my raw notes to fill out that specific template.
5.  Provide me with *only* the final, filled-out HTML/Markdown code block. Do not provide any other text.

---
**[START CONTRIBUTING.MD CONTENT]**
[Paste the full contents of your CONTRIBUTING.md file here every time you run this prompt]
---
**[START RAW NOTES]**
[Paste your new, unstructured notes here]
---
```
</details>

## ✍️ Excel-Contributions

<details> 
<summary> 
    <strong>➡️ Click to copy the Excel Formula Template</strong> 
</summary>
<br>

> Note: Copy the code block below to add a new Excel formula to the main Excel-formulas.md.

<details>
<summary>
  <strong>➡️ [Name of Your Goal (e.g., Split Text by a Dash)] ([FORMULA NAME])</strong>
  <br>
  <small>[A 1-sentence description of what this formula achieves.]</small>
</summary>
<br>

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
