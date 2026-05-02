# TaskFlow - Collaborative Team Task Manager

TaskFlow is a modern, full-stack project management application designed for teams to collaborate on projects, track tasks, and monitor progress in real-time. Built with a sleek glassmorphic design and a robust backend.

![Screenshot](/public/screenshot.png) <!-- Note: Add a screenshot to your public folder if you have one -->

## 🚀 Features

- **User Authentication**: Secure JWT-based login and registration.
- **Project Management**: Create projects, add team members, and manage project lifecycles.
- **Task Tracking**: Assign tasks, set priorities (Low, Medium, High), and track statuses (To Do, In Progress, Done).
- **Team Collaboration**: Admins can manage team members and assign tasks to specific users.
- **Dynamic Dashboard**: Visual overview of task statistics, overdue items, and workload distribution.
- **Modern UI**: Dark mode, glassmorphic panels, and smooth animations.

## 🛠️ Tech Stack

- **Frontend**: Next.js 15+, React 19, Lucide React (Icons)
- **Backend**: Next.js Route Handlers (API)
- **Database**: SQLite (Development) / PostgreSQL (Production) via Prisma ORM
- **Authentication**: JWT with `jose` and `bcryptjs`
- **Styling**: Vanilla CSS (Custom Glassmorphism System)

## 📦 Getting Started

### Prerequisites

- Node.js 18+ 
- A database (SQLite is used by default, but PostgreSQL is recommended for production)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/task-manager.git
   cd task-manager
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Initialize Database**:
   ```bash
   npx prisma generate
   npx prisma db push
   ```

4. **Run the development server**:
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser.

