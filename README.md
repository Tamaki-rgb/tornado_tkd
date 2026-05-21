# Tornado TKD — Digital Journal for Taekwondo Coach

**Full-stack PWA application** that helps taekwondo coaches manage their clubs efficiently — from attendance tracking to payments and performance analytics.

Built for my own taekwondo club in Shymkent, Kazakhstan. Currently used by the head coach to manage **100+ students**.

### Key Features

- **Group Management** — Create and manage training groups with schedules
- **Attendance Journal** — Automatic daily attendance sheets with monthly navigation
- **Payment Tracking** — Full payment history and status for each student
- **Live Timer** — Customizable round timer with sound alerts for sparring and training
- **Student Profiles** — Detailed information (name, IIN, contacts, parents' phones)
- **Analytics & Statistics** — Performance insights, attendance rates, payment statistics, and group activity overview
- **Dual Coach Access** — Two coaches can work in the same database in real-time
- **PWA** — Installable on phone (works like a native app) with dark/light theme support

### Technologies

- **Frontend**: Vanilla HTML, CSS, JavaScript (no heavy frameworks — maximum performance and lightweight)
- **Backend/Database**: Supabase (PostgreSQL + Auth)
- **PWA**: Progressive Web App — can be added to home screen on both iOS and Android
- **Deployment**: Vercel

### Why I Built It

Instead of using paper journals and Excel files, I created a convenient digital tool that saves the coach dozens of hours per month and gives clear data insights about the club's performance.

### Screenshots


### Live Demo
https://tornado-tkd.vercel.app

### How to Run Locally / Deploy

1. Clone the repository
2. Create a new project on [Supabase](https://supabase.com)
3. Run the SQL setup script (located in the app)
4. Add your Supabase URL and anon key
5. Deploy instantly on Vercel (static hosting)

---
