# ChurchTrack — Church Management System

A full-featured, cloud-based church management system built specifically for Nigerian churches. Developed by MOA World Limited.

## Live Demo
🔗 [Try the live demo](https://churchtrack-demo.netlify.app)
🌐 [Landing page](https://churchtrack-landing.netlify.app)

## Features

### Member Management
- Separate sections for Workers and Members
- Worker ranks — Pastor, Minister, Deacon/Deaconess, HOD, Choir, Ushering and more
- Full member profiles — name, phone, email, gender, birthday, marital status, student status
- Real-time search and filtering

### Attendance Tracking
- Time-stamped check-in for workers
- Separate attendance views for Workers and Members
- Gender breakdown (Male/Female count) on dashboard
- Export attendance report as Excel/CSV file
- Full attendance history by date

### Communication (3-in-1)
- **Email** — Welcome, broadcast, absent checkup, HOD messages, attendance reports to Pastor
- **WhatsApp** — One-click pre-filled messages for greetings, birthdays, absent checkups
- **SMS** — Bulk SMS via Termii to individuals or groups

### Automation
- Auto birthday greetings sent every morning
- Auto welcome email when new member is added
- Email templates and history log
- Attendance report auto-generated and emailed to Pastor

### Security & Access
- Secure admin login with session management
- Forgot password flow
- Cloud sync across all devices in real time

### Admin Portal (for service providers)
- Manage all client churches from one dashboard
- Client onboarding wizard — generates SQL, credentials and deployment guide
- Payment tracking with due date alerts
- WhatsApp payment reminders
- Demo request tracking and conversion

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML, CSS, Vanilla JavaScript |
| Database | Supabase (PostgreSQL) |
| Hosting | Netlify (with serverless functions) |
| Email | Gmail SMTP via Nodemailer |
| SMS | Termii API |
| Fonts | Google Fonts (Playfair Display, DM Sans) |

## Project Structure
## Installation

### Option 1: Clone and Run Locally
```bash
git clone https://github.com/michaeladeyemi3701/churchtrack.git
cd churchtrack
# Open index.html in your browser
