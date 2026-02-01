# My First Webpage

This is my very first full-stack website built from scratch in 12 days! It includes multi-page navigation, dark mode toggle, contact form with real email and DB save, protected dashboard, login/logout, and a realtime blog with Supabase.

## Features
- **6 Pages**: Home, About, Contact, Dashboard, Login, Blog
- **Dark Mode Toggle** on all pages
- **Contact Form**: Sends email via Formspree + saves to Supabase DB
- **Dashboard**: Shows saved contact messages (protected — login required)
- **Blog Feed**: Post messages in real-time, see instant updates across tabs/browsers (Supabase realtime)
- **Authentication**: Login with email/password via Supabase Auth
- **Responsive Design**: Mobile-friendly layouts with consistent styling

## Tech Stack
- HTML5 / CSS3 / Vanilla JavaScript
- Supabase (Auth, Database, Realtime)
- Formspree (Email Service)
- GitHub (Version Control)

## Setup
1. Clone the repo: `git clone https://github.com/zekiali/My-first-webpage`
2. Open in VS Code
3. Run locally: Open any `.html` file in your browser, or deploy to GitHub Pages

## Key Pages

| Page | Features |
|------|----------|
| **Home (index.html)** | Welcome, navigation, dark mode |
| **About (about.html)** | Bio, profile image, goals |
| **Contact (contact.html)** | Contact form, email + DB save |
| **Dashboard (dashboard.html)** | View all contact messages, refresh button, realtime updates |
| **Login (login.html)** | Email/password login, sign up, Google OAuth |
| **Blog (blog.html)** | Post messages (login required), realtime feed with author emails |

## How It Works

### Contact Form Flow
1. User fills out contact form
2. Data sent to Formspree (email) + Supabase DB (saved)
3. Appears on Dashboard (only for logged-in users)

### Blog Realtime
1. Logged-in user posts a message
2. Message instantly appears in feed on all open tabs/browsers
3. Uses Supabase realtime subscriptions (no manual refresh)

## Built by Zeki in Philadelphia, January 2026 🚀
