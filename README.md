# Website
A professional website for a resturant
# 🍽️ Govindam Retreat — Royal Vegetarian Dining

A modern, responsive landing page and web application built for **Govindam Retreat**, an authentic vegetarian Rajasthani dining experience located near Govind Dev Ji Temple, Jaipur.

---

## 📖 Table of Contents
- [Overview](#-overview)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [How It Works](#-how-it-works)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Deployment (Live Demo)](#-deployment)
- [License](#-license)

---

## 🌟 Overview
Govindam Retreat brings traditional Rajasthani royal hospitality to the digital space. The website provides visitors with a rich visual showcase of the royal thali, dynamic digital menu browsing, interactive basket feedback, and an instant table booking interface.

---

## ✨ Key Features

- **Royal Rajasthani Aesthetic:** Custom palette utilizing royal saffron, cream, wine-dark, and gold accents with typography powered by *Fraunces* and *DM Sans*.
- **Responsive Layout:** Fully optimized for seamless viewing across smartphones, tablets, and desktop displays.
- **Interactive Menu & Thali Showcase:** Categorized food cards with pricing, descriptions, and interactive selection.
- **Booking Modal:** Integrated reservation overlay with date, time, and guest-count selectors.
- **Basket Feedback System:** Real-time feedback and state management for item additions and order simulation.
- **Accessibility & Performance:** Built with ARIA labels, semantic HTML5 structure, reduced-motion queries, and preconnected Google Font loaders.
- **Local Directions & Contact:** Direct quick-actions for phone reservations and Google Maps navigation.

---

## 🛠️ Tech Stack

- **Markup:** HTML5 (Semantic Structure)
- **Styling:** Modern CSS3 (CSS Variables, Flexbox, CSS Grid, Media Queries)
- **Scripting:** Vanilla JavaScript (ES6+)
- **Typography:** Google Fonts (`Fraunces`, `DM Sans`)
- **Icons & Assets:** Native SVG & optimized WebP/PNG formats

---

## ⚙️ How It Works

1. **Navigation & Announcement:** A fixed header monitors page scroll state (`.nav.scrolled`) to apply glassmorphism shadows and compact styling dynamically.
2. **Modal Controller:** The booking trigger activates an overlay container via JavaScript event listeners while managing body scroll locks.
3. **Cart & Basket State:** Client-side interaction tracking handles item selection and provides instant visual confirmation without page reloads.

---

## 📂 Project Structure

```text
├── index.html        # Main landing page markup, styles, and logic
├── README.md         # Project documentation and specifications
