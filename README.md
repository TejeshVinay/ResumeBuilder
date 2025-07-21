
# Resume Builder

A real-time, browser-based Resume Builder that allows users to select templates, enter personal and professional information, and download a professional resume as a PDF — all without needing a backend server.

---

## 🚀 Project Overview

This project was developed as part of a final-year B.Tech project in Artificial Intelligence & Machine Learning at **Gokaraju Rangaraju Institute of Engineering and Technology**.

### ✨ Features
- 🎨 Multiple professional resume templates
- 🧾 Dynamic form for inputting user data
- 💾 Auto-saving resume data using browser localStorage
- 📄 PDF export using jsPDF and html2canvas
- 💻 Client-side only – no backend required

---

## 📂 Folder Structure

```
ResumeBuilder/
├── assets/templates/         # Thumbnail images for template previews
├── resumebuilder/
│   ├── form.html             # User input form
│   ├── templatepage.html     # Template selection page
│   └── ...                   # Supporting pages and scripts
├── .gitignore                # Hides resume_templates from GitHub
├── README.md                 # Project readme (this file)
```

---

## 🛡️ Access Control Notice

> ⚠️ The folder `resume_templates/` is intentionally excluded from this repository to prevent unauthorized copying or redistribution of proprietary resume layouts.

If you clone this repository, you can still:
- View the template selection interface
- Fill out the resume form
- See dynamic data handling via localStorage
- Understand how the PDF generation is triggered
- Learn from the architecture and client-side logic

---

## 🛠️ Technologies Used

| Technology      | Purpose                                      |
|----------------|----------------------------------------------|
| HTML5           | Structure of pages                           |
| CSS3            | Responsive and styled layouts                |
| JavaScript (ES6)| Interactivity, data handling, template logic |
| jsPDF           | PDF export functionality                     |
| html2canvas     | HTML to image conversion for PDF             |
| localStorage    | Data persistence in browser                  |

---

## 📥 How to Use

1. **Clone the repo**:
   ```bash
   git clone https://github.com/YourUsername/ResumeBuilder.git
   ```

2. **Open the application**:
   - Open `index.html` in a browser.
   - Select a resume template.
   - Fill in your details in the form.
   - Generate and download your resume as a PDF.

> 📌 Best viewed on modern desktop browsers like Chrome or Firefox.

---

## 👨‍💻 Authors

- **Tejesh Vinay Ch** – 23241A66E2  
- **Venkatesh N** – 23241A66H2  
- **Vineeth Reddy P** – 23241A66H4  

**Under the guidance of:**  
*V. Manasa, Assistant Professor, AIML Department*

---

## 📜 License

```
This project is proprietary. The resume templates and design layouts are protected
and not included in the repository. You may view the source for educational purposes only.

Redistribution, commercial use, or reuse of resume templates is strictly prohibited
without prior written permission from the authors.
```

---

## 📌 Acknowledgments

- Gokaraju Rangaraju Institute of Engineering and Technology
- jsPDF – [https://github.com/parallax/jsPDF](https://github.com/parallax/jsPDF)
- html2canvas – [https://html2canvas.hertzen.com/](https://html2canvas.hertzen.com/)
- Mozilla MDN – Documentation for Web APIs

---

© 2025 ResumePro Team. All rights reserved.
