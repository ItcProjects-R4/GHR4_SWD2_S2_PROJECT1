# AZ-Learn 🚀

AZ-Learn is a modern, responsive educational and learning management platform built with React and Vite. It provides an intuitive interface for students to browse courses, track their progress, analyze course data, and compete on a leaderboard.

## ✨ Key Features

- **Authentication**: Secure Login and Registration flows.
- **Dashboard**: A comprehensive dashboard summarizing user activity and progress.
- **Course Management**:
  - Browse and search available courses.
  - Create new courses.
  - Full-screen, immersive Course Player.
  - **Course Analyzer & Comparison**: Advanced tools to analyze and compare different courses.
- **Leaderboard**: Gamified learning experience to track rankings.
- **Settings & Upgrades**: User profile management and premium feature upgrades.
- **Responsive Design**: Beautiful, mobile-friendly UI powered by TailwindCSS and Flowbite.

## 🛠️ Tech Stack

- **Frontend Framework**: [React 19](https://react.dev/) + [Vite](https://vitejs.dev/)
- **Routing**: [React Router DOM v7](https://reactrouter.com/)
- **Styling**: [TailwindCSS](https://tailwindcss.com/) & [Flowbite React](https://flowbite-react.com/)
- **Forms & Validation**: [Formik](https://formik.org/) & [Yup](https://github.com/jquense/yup)
- **Icons**: [Lucide React](https://lucide.dev/)
- **Linting**: [ESLint](https://eslint.org/)

## 🚀 Getting Started

Follow these steps to set up the project locally.

### Prerequisites

- Node.js (v18 or higher recommended)
- npm or yarn

### Installation

1. **Clone the repository** (if applicable) or navigate to the project directory:
   ```bash
   cd AZ_Learn
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm run dev
   ```
   The app will be available at `http://localhost:5173` (or another port provided by Vite).

## 📜 Available Scripts

- `npm run dev`: Starts the Vite development server.
- `npm run build`: Builds the app for production to the `dist` folder.
- `npm run lint`: Runs ESLint to check for code quality issues.
- `npm run preview`: Locally previews the production build.

## 📂 Project Structure Overview

```text
src/
├── components/   # Reusable UI components
├── Layout/       # Layout components (e.g., DashboardLayout)
├── pages/        # Page-level components (Dashboard, Courses, Login, etc.)
├── services/     # API integration and external services
├── store/        # Global state management
├── App.jsx       # Main application entry point
├── router.jsx    # Application routing configuration
└── main.jsx      # React DOM rendering
```
