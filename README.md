# EventHall — Venue Discovery & Event Inquiry Website

A responsive **HTML/CSS/JavaScript** web storefront for browsing event spaces, exploring venue details, and submitting date inquiries. Designed with a warm editorial aesthetic (champagne gold, daylight ivory, and evening charcoal) that adapts smoothly across desktop, tablet, and mobile browsers.

> **Prototype Notice:** This repository contains the front-end website prototype. Connect the inquiry form and venue listings to your shared backend API before treating availability, quotes, or reservations as live.

---

## Preview

![EventHall Preview](<Screenshot 2026-11-14 141419.png>)

---

## Key Features

- **Responsive Web Layout:** Adapts seamlessly across wide laptop monitors, tablets, and mobile viewports with clean grid layouts and readable content widths.
- **Venue Exploration & Filtering:** Showcases featured spaces (*The Grand Hall*, *The Gallery Room*, *The Courtyard*) with guest capacity details, event category tags (`Weddings`, `Celebrations`, `Corporate`), and amenity highlights.
- **Interactive Date Inquiry Form:** Client-side validated inquiry form allowing visitors to choose an event type, preferred space, estimated guest count, event date, time window, and contact details.
- **Event Status & Trust Transparency:** Clear breakdown of the booking lifecycle (*Inquiry received* → *Quote and review* → *Reservation confirmed*) with explicit advisory notices that inquiries do not automatically reserve dates.
- **Editorial Brand Palette:** Styled with warm ivory (`#F7F5EF`), deep charcoal (`#151714`), and champagne gold (`#B08B53`) accents.

---

## Project Structure

```text
eventhall-web/
├── index.html                           # Main HTML structure and page sections
├── style.css                            # Responsive styling, layout grids, and color tokens (if separated)
├── script.js                            # Interactive filtering and form validation (if separated)
├── Screenshot 2026-11-14 135945.png     # Website preview screenshot
└── README.md                            # Project documentation
