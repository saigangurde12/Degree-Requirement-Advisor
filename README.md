# 🎓 Degree Requirement Advisor AI Agent

An AI-powered academic planning assistant designed to help engineering students understand degree requirements, track academic progress, calculate SGPA and CGPA, monitor backlogs, and plan their journey toward graduation.

The application is tailored for students following **Savitribai Phule Pune University (SPPU)** engineering programs, with configurable academic rules for the applicable regulation and admission year.

## ✨ Features

- **🎯 Academic Eligibility:** Review academic progress against configured university requirements.
- **🧮 SGPA & CGPA Calculator:** Calculate semester-wise SGPA and cumulative CGPA using subject credits and grade points.
- **📊 Percentage Conversion:** Estimate percentage from CGPA using the applicable university conversion formula.
- **📚 Credit Tracking:** Track earned credits and remaining credits required for graduation.
- **⚠️ Backlog & ATKT Tracking:** Record failed subjects and identify potential academic progression concerns.
- **📅 Semester Planning:** Organize pending subjects, credits, and academic priorities.
- **🤖 AI Academic Assistant:** Ask questions about academic requirements and receive personalized guidance.
- **📈 Progress Dashboard:** View academic performance, completed credits, pending subjects, and progress toward graduation.
- **🇮🇳 Indian Education System:** Support Indian engineering terminology, semester structures, credit systems, and applicable university regulations.

## 🎓 Target Students

- University: Savitribai Phule Pune University (SPPU)
- Degree: B.E. / B.Tech
- Branch: Computer Engineering
- Regulation: NEP / applicable SPPU pattern
- Education System: Indian higher education

**Important:** Academic rules can vary by admission year, course, and applicable university ordinance. Verify eligibility, ATKT, credit requirements, and grade-conversion rules against official SPPU documents before making academic decisions.

## 🛠️ Technology

The technology stack depends on the generated application. It may include:

- AI-assisted academic guidance
- Web-based user interface
- SGPA and CGPA calculation logic
- Academic progress visualization
- Configurable university rules

Update this section to list the exact frameworks, libraries, and AI services used by your implementation.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### 2. Open the project

```bash
cd YOUR-REPOSITORY
```

### 3. Install dependencies

Follow the installation instructions for the framework and package manager used by your project. For example, if the project uses npm:

```bash
npm install
```

### 4. Configure environment variables

If your application uses an external AI API, create a `.env` file and configure the required environment variables according to the project's setup instructions.

**Security:** Never commit API keys, passwords, or other secrets to GitHub. Keep private keys on the server side where appropriate.

### 5. Run the application

For an npm-based project, the development command may be:

```bash
npm run dev
```

Check `package.json` for the actual scripts supported by your project.

## 🧮 SGPA and CGPA

The application can use credit-weighted calculations.

**SGPA:**

\[
SGPA = \frac{\sum (C_i \times G_i)}{\sum C_i}
\]

Where:
- \(C_i\) = credits for a subject
- \(G_i\) = grade points earned in that subject

**CGPA:** Calculated using the applicable cumulative credit-weighted formula across completed semesters.

Percentage conversion must follow the formula prescribed for the student's applicable SPPU regulation. Do not assume one conversion formula applies to every admission batch.

## 🔒 Responsible Use

- Treat AI-generated advice as guidance, not an official university decision.
- Verify academic eligibility and graduation requirements with the university or college.
- Do not enter unnecessary personal or confidential information.
- Confirm calculations against official marksheets and university rules.

## 🗺️ Future Enhancements

- Student profile and academic history
- Subject-wise credit and grade entry
- Downloadable academic progress reports
- Personalized study and backlog-clearing plans
- Notifications for important academic deadlines
- Support for additional Indian universities
- Verified, regulation-specific eligibility checks

## 🤝 Contributing

Contributions, bug reports, and feature suggestions are welcome. Please open an issue to discuss significant changes before submitting a pull request.

## 📄 Disclaimer

This is an educational planning tool and is not affiliated with or officially endorsed by Savitribai Phule Pune University. University regulations and academic eligibility must be confirmed using the applicable official documents.

## 👨‍💻 Author

**Sai Gangurde**

⭐ If you find this project useful, consider giving the repository a star!
