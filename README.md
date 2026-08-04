# TicketTap 🎬
 
A full-stack movie ticket booking platform where users can browse movies, pick seats, pay online, and manage their bookings — with a full admin dashboard to manage movies, showtimes, and bookings.
 
**Live demo:** [https://tickettap-movies.vercel.app/](https://tickettap-movies.vercel.app/)
 
---
 
## Features
 
**For users**
- Browse now-showing movies with real-time data (posters, cast, synopsis, trailers) pulled live from the TMDB API
- View detailed movie pages (cast, synopsis, showtimes)
- Interactive seat-selection layout for booking
- Secure payments via Stripe Checkout
- Automatic seat release if payment isn't completed in time (prevents seats being held indefinitely)
- Save favorite movies
- Authentication via Clerk
  
**For admins**
- Dashboard overview of bookings and activity
- Add / edit / remove movies and showtimes
- View and manage all bookings
---
 
## Tech Stack
 
| Layer      | Technology                          |
|------------|--------------------------------------|
| Frontend   | React, Tailwind CSS, JavaScript      |
| Backend    | Node.js, Express (RESTful API)                     |
| Database   | MongoDB (Mongoose)                   |
| Auth       | Clerk                                |
| Payments   | Stripe (Checkout + Webhooks)         |
| Email      | Nodemailer (booking confirmations & reminders) |
| Deployment | Vercel (frontend), Render (backend)          |
 
---
