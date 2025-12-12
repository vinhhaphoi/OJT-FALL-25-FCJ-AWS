# 📋 AWS FCJ Internship Report

> **VinhDQSE180012** | OJT Fall 2025 - AWS First Cloud Journey Internship Program

[![Hugo](https://img.shields.io/badge/Hugo-FF4088?style=for-the-badge&logo=hugo&logoColor=white)](https://gohugo.io/)
[![Cloudflare Pages](https://img.shields.io/badge/Cloudflare%20Pages-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)](https://pages.cloudflare.com/)

🔗 **Live Demo:** [https://report.vinhhaphoi.com](https://report.vinhhaphoi.com)

---

## 👤 Student Information

| Field          | Details                               |
| -------------- | ------------------------------------- |
| **Full Name**  | Dao Quang Vinh                        |
| **Email**      | VinhDQSE180012@fpt.edu.vn             |
| **University** | FPT University                        |
| **Major**      | Software Engineering                  |
| **Company**    | Amazon Web Services Vietnam Co., Ltd. |
| **Position**   | FCAJ Intern                           |
| **Duration**   | September 2025 - December 2025        |

---

## 📁 Report Structure

| Section                    | Description                                     |
| -------------------------- | ----------------------------------------------- |
| **1. Worklog**             | Weekly work logs documenting tasks and progress |
| **2. Proposal**            | Project proposal for the internship             |
| **3. Translated Blogs**    | AWS blogs translated into Vietnamese            |
| **4. Events Participated** | AWS events attended during internship           |
| **5. Workshop**            | Self-built workshop on Amazon QuickSight        |
| **6. Self-evaluation**     | Personal assessment of internship performance   |
| **7. Sharing & Feedback**  | Feedback and sharing from the internship        |

---

## 🛠️ Technology Stack

- **Static Site Generator:** [Hugo](https://gohugo.io/) with `hugo-theme-learn` theme
- **Deployment:** [Cloudflare Pages](https://pages.cloudflare.com/)
- **Languages:** English & Vietnamese (Bilingual support)

---

## 🚀 Getting Started

### Prerequisites

- [Hugo](https://gohugo.io/installation/) (Extended version)
- [Node.js](https://nodejs.org/) (v18+)
- [Git](https://git-scm.com/)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/vinhhaphoi/OJT-FALL-25-FCJ-AWS.git
   cd OJT-FALL-25-FCJ-AWS
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Initialize submodules (for theme):**

   ```bash
   git submodule update --init --recursive
   ```

4. **Run development server:**

   ```bash
   hugo server -D
   ```

5. **Open in browser:**
   ```
   http://localhost:1313
   ```

### Build for Production

```bash
hugo --minify
```

The built site will be in the `public/` directory.

---

## 📂 Project Structure

```
OJT-FALL-25-FCJ-AWS/
├── archetypes/          # Content templates
├── content/             # Markdown content files
│   ├── 1-Worklog/       # Weekly work logs
│   ├── 2-Proposal/      # Project proposal
│   ├── 3-BlogsTranslated/
│   ├── 4-EventParticipated/
│   ├── 5-Workshop/
│   ├── 6-Self-evaluation/
│   └── 7-Feedback/
├── layouts/             # Custom layouts
├── static/              # Static assets (images, etc.)
├── themes/              # Hugo theme (hugo-theme-learn)
├── config.toml          # Hugo configuration
└── package.json         # Node.js dependencies
```

---

## 🌐 Deployment

This site is automatically deployed to **Cloudflare Pages** on push to the main branch.

---

## 📝 License

This project is created for educational purposes as part of the AWS First Cloud Journey Internship Program at FPT University.

---

## 📧 Contact

- **GitHub:** [@vinhhaphoi](https://github.com/vinhhaphoi)
- **Facebook:** [vinhhaphoi2](https://www.facebook.com/vinhhaphoi2/)
- **Email:** its.vnhdq@gmail.com
