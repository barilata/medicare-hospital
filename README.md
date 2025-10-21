# 🏥 MediCare Hospital - Online Appointment Booking System

![Project Banner](https://medicare-hospital01.netlify.app/)

### 🌐 Live Demo  
👉 **[Visit Here](https://medicare-hospital01.netlify.app/)**  

---

## 📖 Introduction

**MediCare Hospital Appointment Booking System** is a modern, web-based application that allows patients to easily book hospital appointments online.  
The project is built using **React (TypeScript)** with **Tailwind CSS** and **ShadCN UI** for a responsive and visually appealing interface.  

It integrates **EmailJS** for automating communication — sending confirmation emails to both patients and hospital administration upon successful appointment submission.  
Recently, **Supabase** integration was added to store and manage client appointment data efficiently.

---

## 🎯 Objectives

- To develop a user-friendly and responsive appointment booking system.
- To automate email communication using **EmailJS**.
- To store patient details securely in **Supabase**.
- To enhance the user experience through smooth form validation and transitions.
- To provide a scalable foundation for future enhancements like login, admin panel, and tracking.

---

## 🛠️ Tech Stack

| Category | Technology Used |
|-----------|----------------|
| **Frontend Framework** | React (TypeScript) |
| **Styling** | Tailwind CSS |
| **UI Library** | ShadCN UI |
| **Email Automation** | EmailJS |
| **Database** | Supabase |
| **Date Handling** | date-fns |
| **Version Control** | Git & GitHub |
| **Editor** | Visual Studio Code |
| **Deployment** | Netlify |

---

## 🧩 Features

✅ Multi-step appointment booking form  
✅ Automated email confirmation via EmailJS  
✅ Real-time input validation  
✅ Responsive design (mobile & desktop friendly)  
✅ Data stored in Supabase for future access  
✅ Clean and modern UI using ShadCN components  

---

## 🧱 Project Structure

MediCare-Hospital/
│
├── src/
│ ├── components/ # Reusable UI components
│ ├── pages/ # Main page components
│ ├── hooks/ # Custom React hooks
│ ├── utils/ # Helper functions (date-fns, etc.)
│ ├── App.tsx # Root app component
│ ├── main.tsx # Entry point
│
├── public/ # Static assets
├── package.json # Project dependencies
├── tailwind.config.js # Tailwind configuration
├── tsconfig.json # TypeScript configuration
└── README.md # Documentation file


---

## ⚙️ Installation & Setup

Follow these steps to run the project locally:

```bash
# Clone the repository
git clone https://github.com/yourusername/MediCare-Hospital.git

# Navigate to the project directory
cd MediCare-Hospital

# Install dependencies
npm install

# Run the app
npm run dev
