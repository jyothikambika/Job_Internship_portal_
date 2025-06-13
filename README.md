# 💼 Job Portal System (React + Vite)

A modern and responsive **Job Portal** built using **React**, **Vite**, and **Material UI (MUI)** that allows users to browse and filter job listings. It includes categorized job postings, search filters, contact information, and social media integration.

---

## 🚀 Features

* 🖥️ **Fast UI** powered by **Vite** and **React 18**
* 🎨 **Material UI** for modern design elements and icon support
* 🔎 Job search by **category, location, type, experience**
* 📂 Job data dynamically managed via `Constants.jsx`
* 📞 Contact section with address, phone, email
* 🌐 Social media links integration (LinkedIn, Instagram, YouTube, etc.)
* 📑 Filtered job listings with categories, responsibilities, qualifications, and benefits

---

## 📦 Tech Stack

| Tech        | Role                    |
| ----------- | ----------------------- |
| React       | Frontend framework      |
| Vite        | Development bundler     |
| Material UI | UI components and icons |
| JavaScript  | Programming language    |
| ESLint      | Code linting            |

---

## 🛠️ Project Setup

### 🔧 Installation

```bash
git clone https://github.com/your-username/job-portal.git
cd job-portal
npm install
npm run dev
```

Your application should now be running on `http://localhost:5173`.

---

## 📁 Project Structure

```bash
.
├── Constants.jsx         # Static data for job listings, categories, and UI icons
├── eslint.config.js      # ESLint configuration for clean code
├── package-lock.json     # Dependency lockfile
├── README.md             # Project documentation
├── public/               # Static assets
├── src/                  # Application source code
│   ├── components/       # Reusable UI components
│   ├── pages/            # Pages like Home, BrowseJobs, Contact
│   ├── App.jsx           # Main application component
│   └── main.jsx          # Entry point
└── vite.config.js        # Vite configuration
```

---

## 🧑‍💼 Sample Jobs

Here are a few job titles included in the system:

* **Software Engineer** (Web Development - Remote)
* **UI/UX Designer** (Creative Design - India)
* **Data Scientist** (Data Science - China)
* **Marketing Manager** (Marketing - Australia)
* **DevOps Engineer** (IT Support - Remote)
* **Product Manager** (Operations - Spain)

Jobs are fully categorized with details such as:

* Location (Remote/Onsite)
* Type (Full-time/Part-time)
* Experience Level
* Gender Preference
* Salary Range
* Number of Openings

---

## 🌐 Contact Information

```js
Bengaluru, Karnataka, India
Phone: +91 84558 07965
Email: support@zidio.in
```

---

## 🔗 Social Media

```js
Twitter: https://twitter.com/zidioDev
Instagram: https://instagram.com/zidiodev
YouTube: https://www.youtube.com/@zidioDevelopment
LinkedIn: https://www.linkedin.com/company/zidio-development/posts/?feedView=all
```

---

## 📦 Dependencies

Core packages from `package-lock.json`:

* `react` `^18.3.1`
* `@mui/material` `^6.0.1`
* `@mui/icons-material` `^6.0.2`
* `react-router-dom` `^6.26.2`
* `react-loader-spinner` `^6.1.6`
* ESLint plugins: `react`, `react-hooks`, `react-refresh`, etc.

---

## 🧹 ESLint Rules

Configured in `eslint.config.js`:

* Uses recommended rules for React + Hooks
* React 18 JSX runtime
* Disabled `react/jsx-no-target-blank`
* Warn-only rule for `react-refresh` constant exports

---

## 📌 Future Enhancements

* Add job application forms
* Backend integration for real job data and login/signup
* Admin dashboard for job posting
* Bookmark and save jobs feature
