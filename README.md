# 🏛️ Campus Club Event Hub

A responsive, lightweight web application built to streamline campus engagement, event discovery, and attendee tracking for student organizations and college clubs.

---

## 🌟 Key Features

### 🎓 Student / Public Portal
- **Hero & Highlights:** Club introduction, key statistics, and a spotlight banner for featured flagship events.
- **Dynamic Event Discovery:** Real-time search by title/description and one-click filtering by category (*Technical, Cultural, Workshops, Hackathons, Sports*).
- **Seat Availability Tracking:** Real-time calculation of remaining spots and sold-out states.
- **Seamless Registration:** Intuitive booking form capturing student details, college year, department, and contact info.
- **Instant Digital Pass:** Generates a printable event ticket complete with a dynamic QR code and unique reference ID upon registration.

### 🛠️ Admin Dashboard
- **Analytics Overview:** KPI counters for total active events, overall student registrations, and upcoming event schedules.
- **Event Lifecycle Management (CRUD):** Add, update, view, and delete events with date, venue, category, and capacity constraints.
- **Attendee Roster & Check-In:** Filter registrations by event, perform live name/email searches, and toggle check-in verification statuses on event day.
- **CSV Data Export:** One-click export of attendee rosters for offline coordination and desk check-ins.
- **Persistent Storage:** Browser-level `localStorage` syncing with pre-seeded demo records for out-of-the-box demonstration.

---

## 💻 Tech Stack
- **Frontend:** Vanilla HTML5, Modern JavaScript (ES6+)
- **Styling:** Tailwind CSS (Responsive mobile-first layout)
- **Icons:** Lucide Icons
- **Storage:** Client-side Web Storage API (`localStorage`)
