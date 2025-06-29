# Travina: Smart Travel Planner App

---

## 🔐 Overview

**Travina** is a travel itinerary app focused on trip optimization around personal connections, smart routes, and budget management. The idea: someone is visiting a friend in another city, they input the friend's address, and the app plans everything smartly around that point (lodging, routes, attractions, food, etc).

Primary platform is **mobile app** (React Native + Tailwind). Secondary platform is **marketing/landing website**.

---

## 📅 App Features (Mobile)

### ✈️ Trip Setup

* Input trip name, dates, budget
* Enter destination or friend's address
* App shows nearby:

  * Hotels/Airbnbs
  * Attractions
  * Food deals
  * Local events

### 🗺️ Smart Route Builder

* Drag & drop itinerary view
* Suggests optimized travel sequence (minimize backtracking)
* Distance/time calculator
* Live traffic updates (Google Maps or Mapbox)

### 💸 Budget Manager

* Daily budget setting
* Ticket prices & lodging costs autofill
* Tracks spending throughout trip
* Shows remaining budget in real time

### 🚶️ Things To Do Nearby

* Pulls in:

  * Attractions (TripAdvisor/Google Places)
  * Restaurant offers (Yelp, Groupon)
  * Events (Eventbrite, Facebook Events)
* Smart filters:

  * Price
  * Walkable radius
  * Time required

### 💬 Collab Tools

* Share trips with friends
* Invite-only view/edit access
* Chat & notify inside trip timeline

### 📄 Reservation Manager

* Import Gmail/Yahoo/etc. confirmations
* Auto-adds flights, hotels, car rentals
* Option to manually add (form or photo scan)

### 🕵️ Offline Mode

* Download trip for offline use
* Offline map & saved tickets/info

---

## 🏠 Landing Page (Web)

### ✨ Purpose

* Explain value prop
* Showcase features
* Collect early access emails
* Link to app stores

### 🌐 Sections

1. **Hero Section**

   * "Plan Smarter Trips Around People You Love"
   * CTA button: "Start Planning Now"
   * Background: looping video of planning map

2. **Feature Highlights**

   * Grid layout with icons
   * Examples: Smart Routing, Budget Tracker, Lodging Picker

3. **How It Works**

   * 3-step walkthrough
   * Include app screenshots or mockups

4. **Why Travina?**

   * Speed, intelligence, connections
   * Quote/testimonial cards

5. **Early Access Sign-Up**

   * Input email + dropdown ("I'm a solo traveler" / "Planning for group" / etc.)
   * Email collection + optional interest form

6. **App Store Links**

   * Apple Store + Google Play badges
   * QR code to open mobile app

7. **Footer**

   * About us, contact, social links, privacy, terms

---

## 🎨 UI/UX Design

### General Design Style

* TailwindCSS
* Frosted glass cards + vibrant gradients
* Minimalist icons
* Rounded corners (2xl), shadow-xl
* Accent colors by category (food = orange, hotels = purple, etc)

### App Pages

1. **Trip Dashboard**

   * Trip cards
   * "Start New Trip" + archived trips

2. **Trip Planning View**

   * Map left side
   * Scrollable vertical day list right side
   * Add spot -> auto drop pin -> draggable

3. **Item Detail Screen**

   * Photo, description, link to book/buy
   * Save button + add-to-day dropdown

4. **Budget Screen**

   * Progress bar: spent / left
   * Transaction log (editable)

5. **Chat + Collaborators View**

   * List of contributors
   * Simple message thread for that trip

6. **Reservation Importer**

   * Connect email
   * Permission prompt
   * Parsing visual loader

7. **Offline Mode Toggle**

   * Choose what to download (map, PDF, QR codes, etc)

---

## ⚖️ Technical Stack

* **Frontend:** React Native + Tailwind + Expo
* **Backend:** Node.js or Firebase (auth + trip data)
* **APIs:**

  * Google Maps / Places
  * Yelp / TripAdvisor / Groupon
  * Gmail API
  * Booking.com / Airbnb affiliate APIs
* **Storage:** Firebase Firestore or Supabase

---

## 📊 Launch Plan

1. **Mockup/Prototype** — Figma design for mobile + landing site
2. **MVP Sprint 1** — Basic itinerary builder + trip viewer
3. **Sprint 2** — Reservation importer + budget tracker
4. **Sprint 3** — Friends/collab + chat
5. **Pre-launch Website** — SEO + email list
6. **Launch Beta** — via TestFlight + Play Store
7. **Growth Plan** — college clubs, Reddit travel forums, TikTok reels

---

## 🔎 Notes / Extras

* Include referral system to incentivize shares
* AI-powered day plan auto-generator (future)
* Monetization: premium for offline + smart AI routes
* Accessibility: colorblind safe palette, text scaling

---

Let me know when you want this converted into a Figma prototype or working code setup.
