# MS Artist Makeup — Ghar Baithe Beauty Parlour
> **"Sahi Rate, Har Kaam — Beauty Parlour Ghar Par"**

A luxury, bilingual (English & हिंदी) doorstep beauty parlour and makeup artist booking platform connecting clients with verified local artists across Indian states and districts (Bihar, Uttar Pradesh, Delhi NCR, Rajasthan, Maharashtra, etc.).

---

## 🔑 User Roles & Authentication

### 1. Secret Admin Portal (गुप्त एडमिन पैनल)
- **URL Route:** Accessible directly via `#admin-secret-panel` or `?route=admin-secret-panel` (hidden from all public navigation links as requested).
- **Admin Email:** `gkgmkg345@gmail.com`
- **Admin Password:** `Manish@35`
- **Capabilities:**
  - View all registered artists with **Approve / Reject / Block / Unblock** controls.
  - View all customer appointments and change booking status (Pending, Confirmed, Completed, Cancelled).
  - Manage services catalog & fix rate lists (Add new service, modify starting/standard prices, delete services).
  - Send broadcast notifications / festival offer banners across the website.
  - Track gross revenue and appointment statistics.

### 2. Artist Portal (कलाकार / पार्लर)
- **Registration:**
  - Full Name, Shop / Salon Name, WhatsApp Number, Calling Number
  - Full Address, State (all Indian states), District (dynamic dropdown populated based on state)
  - Profile photo, portfolio samples, years of experience, bio
  - Initial service selection with custom pricing
- **Artist Dashboard:**
  - Toggle online availability status (*Accepting Bookings* vs *Marked as Busy*)
  - View customer requests with 1-click **Accept / Reject**
  - **Direct WhatsApp Chat** with customer
  - Manage individual service pricing
  - View customer ratings & reviews

### 3. Customer Portal (ग्राहक)
- **Search & Filters:**
  - Search by artist name, salon name, state, district, service, price range, and minimum rating.
  - Choose between **Doorstep Home Service (घर पर सेवा)** or **Visit Artist Salon (पार्लर जाएं)**.
  - Instant pre-filled WhatsApp alert generated on booking.
- **Customer Dashboard:**
  - View live booking history and status.
  - Direct WhatsApp chat with the booked artist.
  - Star ratings and reviews for completed appointments.
  - Saved favorite artists for quick rebooking.

---

## 💄 Services & Rate Card (रेट सूची)
Full list of 20 categorized beauty services:
- **Bridal & Festive:** Bridal Makeup (Dulhan), Reception Glam, Engagement Makeup, HD / Airbrush Makeup, Groom Makeup, Kids Styling.
- **Hair Care:** Hair Styling, Curls, Hair Spa, Keratin & Smoothening.
- **Skin Care:** Gold / Diamond / Fruit Facial, Clean-up & Bleach, Rica Waxing, Threading.
- **Mehendi & Nails:** Organic Bridal Mehendi, Gel Nail Extensions, Manicure & Pedicure, Saree Draping, Pre-Bridal Glow Packages.

---

## 🌐 Bilingual Support
- Switch between **English** and **हिंदी** instantly using the language toggle in the header.
- Automatically persists your preferred language in `localStorage`.
