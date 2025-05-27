# 🔗 LaTeX Modern CV Template

Welcome to the **Badredenyx LaTeX CV** project! 🚀
This professional, minimalist, and ATS-friendly “Curriculum Vitae” template is built using modern LaTeX best practices to help you create an elegant and effective resume.

---

## 🌟 Features

* Clean and modern A4 format with European standards
* Fully modular source: separate sections for education, experience, skills, and projects
* Simple to customize and extend
* Professional font and typography setup (Lato)
* Integrated support for French and English with `babel`
* Automatic formatting and spacing
* ATS-compatible hidden text section for keyword optimization
* Personal photo support (passport size recommended)

---

## 📂 Directory Structure

```
badredenyx-latex_cv/
├── custom-commands.tex     # All reusable commands/macros
├── resume.tex              # Main LaTeX resume file (entry point)
└── src/                    # Structured content folder
    ├── education.tex       # Education section
    ├── experience.tex      # Experience section
    ├── heading.tex         # Header: name, contact, profile summary
    ├── projects.tex        # Personal or professional projects
    └── skills.tex          # Skills section
```

---

## ⚖️ Customization Guide

You're free to customize almost every part of this CV to match your style or industry standards. Here's how:

### 1. **Change Contact Details**

Edit `src/heading.tex`:

```latex
\href{mailto:your.email@example.com}{...}
\href{https://www.linkedin.com/in/yourprofile}{...}
\href{https://github.com/yourusername}{...}
```

### 2. **Replace Profile Picture**

Put your photo at `photo/photo.jpg` (3x4 cm). Or remove this line from `resume.tex` to skip the image:

```latex
\includegraphics[width=3cm,height=4cm]{photo/photo.jpg}
```

### 3. **Modify Content Sections**

Each section lives in `src/`:

* Add your education in `education.tex`
* Update your job roles in `experience.tex`
* List side projects in `projects.tex`
* Include your tech stack in `skills.tex`

### 4. **Add New Sections**

Follow the structure used in current `.tex` files. Example:

```latex
\section{Certifications}
\resumeSubHeadingListStart
  \resumeSubheading
    {Certified XYZ}{2025}
    {Issued by ABC Organization}{Online}
\resumeSubHeadingListEnd
```

### 5. **Add or Edit Commands**

Modify `custom-commands.tex` to tweak layout or add your own macros.

---

## ⚡ Quick Start

1. **Install LaTeX** (e.g., TeX Live, MikTeX, Overleaf)
2. **Clone the repository**

```bash
git clone https://github.com/yourusername/badredenyx-latex_cv.git
cd badredenyx-latex_cv
```

3. **Compile**
   Use your preferred compiler (e.g., `pdflatex`, `xelatex`, `lualatex`). For example:

```bash
pdflatex resume.tex
```

Or use [Overleaf](https://www.overleaf.com/) for online editing and live previewing.

---


## 🔧 Tech Stack Used

* **LaTeX**: Document preparation
* **Lato**: Modern sans-serif font
* **FontAwesome5**: For icons
* **Babel**: French & English language support

---

## 📊 Hidden ATS Optimization

At the bottom of the CV, there is a white-colored section to paste job descriptions or keyword-dense summaries to boost parsing by ATS systems:

```latex
{\color{white}
\fontsize{1pt}{1pt}\selectfont
ADD THE JOB DESCRIPTION HERE ...
}
```

You can paste any job description here and the text will remain invisible in the final PDF but readable by automated systems.

---

## ✨ Tips for Best Use

* Keep your resume to **1 page** unless your industry allows more
* Use action verbs and quantify impact (e.g., "improved X by Y%")
* Update the ATS section per job to maximize visibility
* Keep photo optional depending on your country’s standards

---

## 🙏 Credits

This template was crafted by **Badr-Eddine Karafli** with inspiration from open-source CV designs, modern LaTeX practices, and a passion for clean design.

Feel free to fork ✨ and star ⭐ this repo if you found it helpful!

---

## 🛠️ License

This project is open-source under the **MIT License**. You're free to use, modify, and distribute with attribution.

> "Simplicity is the ultimate sophistication." — *Leonardo da Vinci*

---

## ✨ Contributions

Found a typo, bug, or want to add features? PRs are welcome!

---

Thank you for checking out this template! Best of luck with your job hunt! 🙌💼
