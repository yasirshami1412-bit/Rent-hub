# Rent-hub# RentHub Bhakkar (رینٹ ہب بھکر)
> **“Har Taqreeb Ke Liye, Sab Kuch Rent Par”**  
> *Everything You Need for Every Occasion in District Bhakkar, Punjab, Pakistan.*

A complete, production-ready, full-stack rental marketplace built specifically for **District Bhakkar** (Bhakkar City, Darya Khan, Mankera, Kallur Kot, Behal, Dullewala, Jandanwala, etc.). 

Built entirely in **HTML, CSS, and JavaScript** with an integrated relational database engine (`localStorage`), role-based authentication, interactive booking workflows, calendar double-booking prevention, vendor & admin dashboards, bilingual English/Urdu support with true Right-to-Left (RTL) layout, and direct WhatsApp vendor coordination.

---

## 🌟 Key Features & Capabilities

### 1. Six Local Rental Categories
- **Marriage Halls & Event Venues**: Grand Koh-e-Noor Wedding Marquee, Al-Razi Banquet Lawn & Hall (capacity up to 1,200 guests, AC, backup generators, bridal suites).
- **Car Rental & Bridal Cars**: White Toyota Land Cruiser Prado (TX Luxury Wedding Edition), Honda Civic Oriel (Black Edition), with uniformed chauffeurs.
- **Photography & Videography**: Thal Studios & Cinematic Films (4K video, DJI Mavic 3 Pro drone coverage, signature velvet albums).
- **Tents & Event Equipment**: VIP German waterproof shamianas, sofa sets, banquet chairs, sound systems, 100kVA Cummins silent diesel generators.
- **Catering & Food Services**: Shahi Dawat wedding feast (Chicken Dum Biryani, Mutton Roghni Qorma, Seekh Kabab, Halwa, ceramic crockery, waiters).
- **Decoration & Stage Setups**: Grand Fresh Rose Stage with floral walkway arches, Yellow Marigold Mehndi & Dholak setups.

### 2. District Bhakkar Geographic Coverage
- Dedicated support for **Bhakkar City**, **Darya Khan**, **Mankera**, **Kallur Kot**, **Behal**, **Dullewala**, **Jandanwala**, **Kotla Jam**, **Panjgirain**, and **Hyderabad Thal**.
- Filters accurately match local service areas.

### 3. Bilingual English & Urdu with Real RTL Layout
- Click the top right **اردو / English** button to switch the entire application interface.
- Automatically toggles `dir="rtl"` with proper Nastaliq typography, flipped flex layouts, translated navigation, cards, forms, and modals.

### 4. Zero Double-Booking Protection & Availability Calendar
- The database engine checks for date conflicts in real-time before booking submission.
- Confirmed bookings automatically lock the calendar date.
- Vendors can also manually block dates for offline bookings or equipment maintenance.

### 5. Server-Grade Price Calculation
Prices adapt to each category’s specific pricing model:
- `per_event`: Fixed event fee.
- `per_day`: Price × duration days.
- `per_hour`: Price × hours.
- `per_person`: Price × number of guests (catering).
- `per_item`: Price × quantity.
- `custom_quotation`: Custom quotation flow.

### 6. Role-Based Portals & Dashboards
- **Customer Dashboard**: Track booking statuses (Pending, Accepted, Confirmed, Completed, Cancelled), cancel eligible requests, and leave verified 5-star reviews for completed functions.
- **Vendor Dashboard**: Overview KPIs (listings, pending requests, confirmed bookings, revenue PKR), manage listings, block dates, accept/reject requests, and open direct WhatsApp chat with clients.
- **Admin Portal**: Platform statistics, verify or suspend vendor businesses, moderate listings, toggle featured status, and inspect system audit logs.

### 7. Direct WhatsApp Coordination
- Generates working `https://wa.me/92...` links pre-filled with the listing title and polite inquiry message.

---

## 🚀 How to Run

Because this project is built cleanly with **HTML, CSS, and JavaScript**:
1. Simply double-click **`index.html`** in File Explorer to open it in any web browser (Chrome, Edge, Firefox, Safari).
2. Alternatively, run with VS Code Live Server or any static HTTP server:
   ```powershell
   # If Python is installed:
   python -m http.server 3000
   ```
   Then open `http://localhost:3000` in your browser.

---

## 🔑 Pre-Seeded Demo Accounts

You can log in manually or click the **"Quick Demo Logins"** buttons inside the Login dialog:

| Role | Email | Password | Details |
| :--- | :--- | :--- | :--- |
| **District Administrator** | `admin@renthub.pk` | `Admin@Bhakkar2026!` | Full platform administration, vendor verification, listing moderation, audit logs |
| **Verified Vendor** | `vendor@renthub.pk` | `Vendor123!` | Royal Marquee owner, booking requests, calendar block, revenue stats |
| **Customer** | `customer@renthub.pk` | `Customer123!` | Ahmed Raza Niazi, booking requests, favorites, verified reviews |

---

## 📂 Project Structure
```
c:\Users\Yasir\Desktop\Rent Hub Web\
├── index.html        # Main responsive single-page web app with all modals & sections
├── index.css         # Complete design system (Navy, Gold, Emerald, RTL Urdu styles)
├── index.js          # Relational storage engine, auth, booking safeguards & workflows
├── README.md         # Full project documentation and user manual
└── legacy\           # Backup archive of previous files
```

---

*Made with dedication for the people and businesses of District Bhakkar, Punjab, Pakistan.*