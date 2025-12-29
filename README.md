Here's a **clean, concise README** focusing only on the project essentials:

```markdown
# GITAM Women Career & Mentorship Platform

A comprehensive digital platform for women students of GITAM University to connect with mentors, access career tools, and discover opportunities.

## Features

### 🔐 Authentication
- Role-based login (Student, Mentor, Admin)
- Secure JWT authentication
- Protected routes based on user role

### 👩‍🎓 Student Dashboard
- View assigned mentor details
- Check upcoming meetings
- Update academic profile and skills
- Access career development tools

### 👩‍🏫 Mentor Portal
- Manage availability status
- Connect with students
- Schedule meetings
- Provide career guidance

### 💬 Real-time Chat
- Instant messaging with mentors/students
- Online/offline status
- Message history

### 🛠️ Career Tools
- Resume builder and parser
- ATS compatibility checker
- Skills roadmap generator
- Interview preparation resources

### 📢 Announcements
- Platform updates and notifications
- Workshop and opportunity alerts
- Category-based filtering

### ⚙️ Admin Panel
- User management
- Mentor approval system
- Announcement posting
- Platform analytics

## Tech Stack

- **Frontend:** React 19, TypeScript, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** PostgreSQL (via Supabase)
- **Authentication:** JWT, Role-based access control
- **Real-time:** WebSocket connections

## Quick Start

1. Clone the repository:
```bash
git clone https://github.com/Aripilli-Bhavana/GITAM-Women-Career-and-Mentoring-Platform-Dept-CSE.git
```

2. Install dependencies:
```bash
npm install
```

3. Start development server:
```bash
npm run dev
```

4. Open browser: `http://localhost:5173`

## Demo Credentials

- **Student:** student@gitam.edu / password123
- **Mentor:** mentor@gitam.edu / password123  
- **Admin:** admin@gitam.edu / password123

## Project Structure

```
src/
├── pages/           # Main application pages
├── components/      # Reusable UI components  
├── hooks/           # Custom React hooks
├── contexts/        # React context providers
└── integrations/    # External service integrations
```

## Key Pages

- `/` - Home page
- `/auth` - Login/Register
- `/dashboard` - Role-based dashboard
- `/mentors` - Mentor listing and chat
- `/career-path` - Career development tools
- `/internships` - Opportunity listings
- `/resume-parser` - Resume analysis tool

## Database

PostgreSQL database with tables for:
- Users (students, mentors, admins)
- Meetings and sessions
- Messages and chats
- Announcements and notifications

## Run Commands

```bash
npm run dev      # Start development server
npm run build    # Build for production
npm run preview  # Preview production build
npm run lint     # Check code quality
```

---

**Department:** Computer Science & Engineering  
**University:** GITAM Deemed to be University
```
