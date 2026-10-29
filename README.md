# Noraze Khan — Multipage CV Portfolio Website

A responsive, multi-page portfolio and curriculum vitae website for **Noraze Khan**, preserving the design colors, typography, assets, and clean student portrait image from the original design system.

---

## 📄 Site Structure & Pages

This website is structured into 6 individual HTML pages interconnected through a sticky navigation header and footer:

1. **[index.html](file:///c:/Users/DELL/Desktop/multipage%20cv/index.html)** — Home & Hero Page
   - Introduces Noraze Khan with his clean portrait photo.
   - Quick bio, title, call-to-action buttons ("View My Projects", "Contact Me").
   - Portfolio overview directory linking to all dedicated subpages.

2. **[about.html](file:///c:/Users/DELL/Desktop/multipage%20cv/about.html)** — About Me Page
   - Comprehensive bio, 7th semester standing, and internship objectives.
   - 3 stat cards: Degree (BS Computer Science / Qarshi University), Expected Graduation (2027), Current CGPA (2.91/4.00).
   - Core focus areas: Web Engineering, Software Architecture (OOP), and AI Exploration.

3. **[skills.html](file:///c:/Users/DELL/Desktop/multipage%20cv/skills.html)** — Technical Skills Page
   - 6 categorized cards:
     - **Programming Languages**: Python, Java, C++, JavaScript
     - **Frontend Development**: HTML5, CSS3, React.js
     - **Backend Development**: Node.js, PHP
     - **Database Technologies**: Database Fundamentals
     - **Tools & Design**: Git, GitHub, VS Code, Figma, AI-powered development tools
     - **Core Concepts**: Object-Oriented Programming (OOP) and Web Development

4. **[projects.html](file:///c:/Users/DELL/Desktop/multipage%20cv/projects.html)** — Featured Projects Page
   - **Fixora — Home Services Platform** (`In Progress`) with connected nodes SVG illustration.
   - **AI Interior Design** (`In Progress | Final Year Project`) with isometric room wireframe SVG illustration.
   - **University Portal** (`Completed | OOP Project`) with academic dashboard layout SVG illustration.

5. **[education.html](file:///c:/Users/DELL/Desktop/multipage%20cv/education.html)** — Education Page
   - Qarshi University, Bachelor of Science in Computer Science (BSCS).
   - 7th Semester | Expected Graduation: 2027 | Lahore, Pakistan | CGPA: 2.91 / 4.00.
   - Key coursework & academic foundations.

6. **[certifications.html](file:///c:/Users/DELL/Desktop/multipage%20cv/certifications.html)** — Certifications & Learning Page
   - **Artificial Intelligence** — Coursera (`Completed`)
   - **Web Development** — Coursera (`Completed`)
   - Continuous learning statement and growth goals.

7. **[contact.html](file:///c:/Users/DELL/Desktop/multipage%20cv/contact.html)** — Contact Page
   - Direct functional `mailto:norazekha01@gmail.com` email link.
   - Verified GitHub link `https://github.com/NorazeAliKhan`.
   - Location: Lahore, Pakistan.
   - Interactive action card with "Email Me" and "View GitHub Profile" buttons.

---

## 🎨 Preserved Design Elements & Assets

- **Colors**:
  - Deep Navy Blue (`#14213D` / `#000A24`)
  - Professional Blue (`#0051D5` / `#2563EB`)
  - Teal Accent (`#049A87` / `#83F6E0`)
  - Off-white canvas (`#F8F9FF`) and elevated white cards (`#FFFFFF`)
- **Student Portrait**:
  - `student-profile.jpg` (High-resolution, clean student photo without any text or watermark).
- **Typography**:
  - `Inter` (Google Fonts) with Material Symbols icons.
- **Responsive**:
  - Fully responsive across desktop, laptop, tablet, and mobile screens.

---

## 🚀 How to Run the Website

### Option 1: Direct File Launch (Fastest)
Double-click `index.html` in Windows File Explorer or run in PowerShell:
```powershell
Start-Process "c:\Users\DELL\Desktop\multipage cv\index.html"
```

### Option 2: Local HTTP Server
Run the included PowerShell server script:
```powershell
powershell -ExecutionPolicy Bypass -File .\serve.ps1
```
This automatically hosts the website at `http://localhost:8080/` and launches your default browser.
