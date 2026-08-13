# 🍽️ The Golden Leaf — Restaurant Reservation Website

A premium, multi-page restaurant website built for the **Client-Side Development** module, Coursework Two. The site gives visitors everything they need to explore the menu, browse the gallery, read reviews, and book a table — all through a fully client-side, interactive experience with no backend server required.

The core functional requirement — a validated web form — is delivered through the **table reservation form**, which collects guest details (name, phone, email, date, time, party size, occasion, and special requests), validates every field with custom JavaScript, and stores confirmed bookings in the browser using `localStorage`.

---

## 🔗 Links

| | |
|---|---|
| **Repository** | https://github.com/Satirtha7/Book-IT |
| **Live Site** | https://satirtha7.github.io/Book-IT/ |

---

## 🛠️ Technologies Used

- Semantic HTML5
- CSS3 (Flexbox, Grid, transitions & keyframe animations)
- Vanilla JavaScript (DOM manipulation, dynamic event handling, `localStorage`)
- jQuery (admin dashboard: live filtering, search, and DOM updates)
- AOS (Animate On Scroll) library for scroll-triggered animations
- Font Awesome for iconography

---

## ✨ Key Features

- **Homepage** with hero section, about content, and live availability stats
- **Dynamic menu page** with category-based filtering
- **Table reservation form** with full client-side validation (regex-based, live + on-submit checks, accessible error messages)
- **Booking confirmation modal** with an auto-generated receipt, saved to `localStorage`
- **Gallery & testimonials** page with scroll-triggered animations
- **Staff portal** with a mock login flow
- **Admin dashboard** for staff — searchable/filterable bookings table, live stats, and CSV export (jQuery-powered)
- **AI receptionist chat widget** concept, with a graceful offline fallback when no backend is available
- **Cookie consent banner**
- Fully **responsive design** across devices

---

## 📁 Site Structure

```
Book-IT/
├── index.html                    # Homepage: hero, about, live availability stats
├── image/                        # Shared favicon and background images
│
├── Bibash Mahat/                 # Reservation system
│   ├── bibash.html                # Table booking form + confirmation modal
│   ├── bibash.css
│   ├── booking.js                 # Handles submission, receipt generation, localStorage save
│   └── storage.js                 # localStorage read/write helpers for bookings
│
├── Prem Kumar Jha/               # Menu, admin dashboard & AI receptionist
│   ├── index.html                  # Menu page (dynamic filtering by category)
│   ├── admin.html                  # Staff dashboard (bookings table, stats, CSV export)
│   ├── admin.css / style.css
│   ├── app.js                      # Navbar, mobile menu, AI chat widget
│   ├── dashboard.js                # jQuery-driven admin table (search/filter/status/export)
│   └── menu.js                     # Dynamic menu data + category filter rendering
│
├── Rohit Bhusal/                 # Gallery, reviews & form validation
│   ├── rohit.html                  # Gallery + guest testimonials
│   ├── rohit.css
│   └── validation.js               # Custom regex validation for the booking form
│
└── Satirtha Dhar/                # Staff login & shared styling
    ├── login.html                  # Staff portal login page
    ├── style.css / responsive.css  # Shared/base styles and responsive breakpoints
    └── utils.js                    # Shared formatting helpers (date, time, booking ID)
```

---

## 👥 Individual Roles & Contributions

### Bibash Mahat — Reservation System Developer
1. Developed the reservation/booking page
2. Designed responsive CSS for the booking interface
3. Implemented booking JavaScript functionality
4. Developed `localStorage`-based booking storage and live table statistics
5. Implemented booking confirmation and receipt download functionality
6. Fixed navigation, footer and social-media links, and added favicon support
7. Tested and debugged the reservation system and responsive layout
8. Maintained GitHub commits and project documentation

### Prem Kumar Jha — Menu & Admin Dashboard Developer
1. Developed the Menu page
2. Implemented responsive styling
3. Added JavaScript menu filtering
4. Developed the Admin Dashboard
5. Implemented jQuery booking search, filtering and statistics
6. Added CSV export functionality
7. Contributed to `app.js` interactions and the AI receptionist widget
8. Managed GitHub commits, debugging and testing

### Rohit Bhusal — Gallery, Reviews & Validation Developer
1. Developed the Gallery and Reviews page (`rohit.html`)
2. Created responsive styling in `rohit.css`
3. Developed client-side reservation validation in `validation.js`
4. Integrated the Cookie Consent Banner
5. Fixed navigation to the Homepage and linked CSS/JavaScript resources
6. Contributed to final project cleanup and integration
7. Regularly committed and maintained his work through the shared GitHub repository

### Satirtha Dhar — Shared Styling & Utilities Developer
1. Completed the Staff Portal Login page (`login.html`)
2. Developed and maintained the shared `style.css`
3. Built `responsive.css` for desktop, tablet, and mobile layouts
4. Wrote reusable JavaScript functions in `utils.js`
5. Handled CSS/script integration and navigation/resource link corrections
6. Tested login behaviour and responsive layouts
7. Carried out GitHub-based refinement, including resource-link corrections and removal of unused CSS
8. Documented his individual contribution

---

## ▶️ How to Run

1. Clone or download this repository.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari) — no build step or server required.
3. To use the table reservation form, navigate to the **Reserve Table** link from any page.
4. To view the admin dashboard, go to the **Staff Portal** (login page) and submit the form — this is a front-end mock login and will redirect straight to the dashboard.

---

## 📝 Notes

- All bookings are stored client-side in the browser's `localStorage`; data will persist between visits on the same browser but will not sync across devices or browsers.
- A cookie consent banner is shown to visitors on their first visit to the site.
- The "Talk to our AI Receptionist" feature expects a backend chat endpoint. Without a backend running, it gracefully falls back to an offline message rather than breaking the page.
- This project was built purely with HTML, CSS, and JavaScript (plus jQuery and the AOS animation library) per the coursework requirement — no server-side code or database.

---

## 📄 License

This project was created for academic purposes as part of a Client-Side Development coursework assignment.
