# Formatting Guidelines for Scientific CVs

> This document sets the formatting standard for all CVs included in this repository. Follow these rules to ensure readability, professionalism, and consistency.

---

## 🖋️ Fonts & Typography

| Element             | Recommended Style                                      |
| ------------------- | ------------------------------------------------------ |
| Body text           | Sans-serif (Arial, Calibri) or serif (Times New Roman) |
| Font size (body)    | 10–11 pt                                               |
| Font size (headers) | 12–14 pt, bold                                         |
| Font color          | Black or very dark gray only                           |
| Line spacing        | 1.15–1.2 (single-spaced with breathing room)           |

> Use the same font family throughout. Avoid mixing fonts unless explicitly required.

---

## 📐 Margins & Spacing

| Element         | Setting                        |
| --------------- | ------------------------------ |
| Margins         | 0.6–0.75 inches on all sides   |
| Section spacing | Extra line space above headers |
| Bullet spacing  | 0.3–0.5 line between items     |

> Keep your document well-structured and not overly dense. White space is part of the design.

---

## 📌 Section Headings

| Rule                                        | Example                  |
| ------------------------------------------- | ------------------------ |
| Use consistent casing                       | ALL CAPS or Title Case   |
| Align left, bold                            | **RESEARCH EXPERIENCE**  |
| Avoid underlining or unconventional symbols | ❌ \~\~\~Experience\~\~\~ |

---

## 🔢 Numbering & Bullets

| Type    | Use for                           |
| ------- | --------------------------------- |
| Bullets | Listing experience/skills/tasks   |
| Numbers | Optional: publications, awards    |
| Dashes  | Only in subheaders or date ranges |

> All bullet points should begin with a **strong verb**, be ≤2 lines, and omit ending periods unless full sentences.

---

## 📎 File & Metadata

* ✅ Save as: `Lastname_Firstname_CV_2025.pdf`
* ✅ Ensure PDF metadata includes your name, title, and institution
* ❌ Avoid `.docx` or `.pages` unless explicitly requested
* ✅ Compress PDF if >1MB

---

## 🎨 Visual Clarity

* Do **not** use color to signify hierarchy unless printing in color is guaranteed
* Avoid overly dense visuals, text boxes, or sidebars
* Use consistent spacing between sections and avoid “wall-of-text” blocks

---

## ✅ LaTeX-Specific Notes

| Guideline                              | Preferred Commands                  |                                        |                                            |
| -------------------------------------- | ----------------------------------- | -------------------------------------- | ------------------------------------------ |
| Use modern classes                     | `moderncv`, `europecv`, or `altacv` |                                        |                                            |
| Set margins with geometry package      | `\usepackage[scale=0.8]{geometry}`  |                                        |                                            |
| Maintain font consistency with XeLaTeX | Use `fontspec`, avoid \`            | Maintain font consistency with XeLaTeX | Use `fontspec`, avoid `\usepackage{times}` |

> Preview your compiled PDF on multiple devices and screen sizes.

---

## 📐 Markdown-Specific Notes (for GitHub CVs)

* Use clear headings (`## EDUCATION`) and bullet points (`- Led project…`)
* Prefer tables for structured data (e.g., Education, Publications)
* Keep lines ≤80–100 characters for GitHub readability
* Use proper spacing between sections
* Link to GitHub repos, DOIs, and personal websites where relevant

---

## 💡 Final Checks

| Checkpoint                           | Why It Matters                      |
| ------------------------------------ | ----------------------------------- |
| Fonts are readable and consistent    | Ensures clarity across screen types |
| Spacing is balanced                  | Improves scannability               |
| Section titles are aligned and clean | Helps committee review quickly      |
| PDF name and metadata correct        | Avoids being lost in file stacks    |

> Run through the full **Checklist.md** to catch any additional issues.

---

## 🧪 Optional Tools

* [latexindent](https://ctan.org/pkg/latexindent) for auto-formatting LaTeX
* [Markdownlint](https://github.com/DavidAnson/markdownlint) for Markdown CVs
* [PDF-XChange Editor](https://pdf-xchange.eu/) or [SmallPDF](https://smallpdf.com/) for compression and preview

> Adhering to a clean formatting standard makes your content shine without distraction.
