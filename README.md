# DashNest

**DashNest** is a dashboard-based, multi-project web application built with **React** and **Vite**, offering a seamless user experience through smooth navigation, responsive design, and powerful state management using Redux. It serves as a central hub for five integrated sub-projects, making it a versatile and educational full-stack frontend application.

## ✨ Features

- 🔐 Login and Registration with form validation
- 🧠 Global state management with **Redux Toolkit**
- 🧩 Includes 5 sub-projects:
  - **Counter App** (Decimal & Number counters)
  - **To-Do App** (Task management)
  - **Movie Search App** (Search movies using a third-party API)
  - **E-Shopping Cart** (Add, remove, and manage products)
  - **Blogging App** (Add and read blog posts)
- 🧭 Sidebar-based layout for easy navigation
- 🎨 Responsive design for all devices
- ⚡ Smooth transitions with **Framer Motion**
- 💡 Icon-rich UI using **React Icons**
- 🔔 Notifications with **React Hot Toast**

## 🗂️ Project Structure
DashNest/
├── src/
│ ├── components/
│ ├── pages/
│ │ ├── Auth/ → Login & Register
│ │ ├── Counter/ → Counter App
│ │ ├── Todo/ → To-Do App
│ │ ├── MovieSearch/ → Movie Search App
│ │ ├── Cart/ → E-Shopping Cart
│ │ └── Blog/ → Blogging App
│ ├── redux/ → Redux Store
│ ├── App.jsx
│ └── main.jsx
├── public/
├── index.html
├── package.json
└── vite.config.js


## 🧠 Tech Stack

- **React** + **Vite**
- **Redux Toolkit** for global state
- **React Router** for navigation
- **Framer Motion** for animations
- **React Icons** for UI enhancement
- **React Hot Toast** for notifications
- **Axios** for API integration
- **ESLint** for code quality

## 🚀 Getting Started

### Prerequisites

- Node.js (version 14 or above)
- npm or yarn

### Installation

```bash
git clone https://github.com/your-username/DashNest.git
cd DashNest
npm install

Run the Application-npm run dev