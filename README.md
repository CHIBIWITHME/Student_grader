# 🧮 Student Grader & Report Generator System

A Python-based student grading and report generation system built using **Jupyter Notebook**, with features like automated score computation, grading, visualizations, and PDF/CSV export.

---

## 🚀 Features

- 📊 Calculates total score, average, and assigns grades automatically.
- 📁 Organizes student results into folders (one per student).
- 📝 Generates a detailed PDF report with subject scores, grades, comments, and summaries.
- 📉 Exports results as CSV and PNG (bar chart of performance).
- 📄 Unicode PDF report support (via `Symbola.ttf`) using `fpdf2`.
- 📂 Saves multiple students and preserves records session-wise and term-wise.

---

## 🔧 How to Use

1. **Open the Jupyter Notebook**

2. **Enter student data** – name, class, subjects, and scores

3. The system will:

   - ✅ Compute grades and average  
   - 🧠 Generate performance comment  
   - 📤 Export:
     - 📄 **PDF report** (`report.pdf`)
     - 📊 **PNG bar chart** (`chart.png`)
     - 📁 **CSV result file** (`<session_term>_result.csv`)
---

## 📦 Requirements

Ensure you have the following installed:

```bash
pip install fpdf2 re os csv textwrap matplotlib datetiime
```
---

### Author
*UGWUANYI, ANTHONY C.*

**LinkedIn:** <a href="https://www.linkedin.com/in/chibi-ugwuanyi-663835252/" target="_blank">chibi-ugwuanyi-663835252/</a>

**E-mail:** <a href="https://mail.google.com" target="_blank">chibiugwuanyi@gmail.com</a>


