# 🚍 FAST Transport System

> 🔴 **A futuristic, intelligent transport assistant for FAST-NUCES Karachi students.** 🟡

<p align="center">

[![Live Demo](https://img.shields.io/badge/🚀_LIVE_DEMO-FAST_TRANSPORT-E31E24?style=for-the-badge)](https://fasttransport.vercel.app/)

[![Routes](https://img.shields.io/badge/🚌_ROUTES-69-FFD700?style=for-the-badge\&labelColor=111111)](#)

[![AI](https://img.shields.io/badge/🤖_AI_ASSISTANT-ENABLED-00D9FF?style=for-the-badge\&labelColor=111111)](#)

[![GPS](https://img.shields.io/badge/📍_GPS-ENABLED-00C853?style=for-the-badge\&labelColor=111111)](#)

[![Weather](https://img.shields.io/badge/🌤️_LIVE_WEATHER-OPEN--METEO-2196F3?style=for-the-badge)](#)

[![Notifications](https://img.shields.io/badge/🔔_NOTIFICATIONS-ENABLED-9C27B0?style=for-the-badge)](#)

</p>

---

## 🌈 Project Overview

**FAST Transport System** is a modern, futuristic web application designed to make transport information easier and faster to access for **FAST-NUCES Karachi students**.

Instead of manually searching through lengthy transport documents, students can instantly find:

> 🚌 **Routes** · 📍 **Nearby Stops** · ⏱️ **Timings** · 📞 **Drivers** · 🤖 **AI Assistance**

The application combines practical transport functionality with an immersive **HUD-inspired interface**, GPS intelligence, personalization, notifications, route comparison, live weather, and voice interaction.

---

# 🔴🟡 Core Transport System

The application currently contains **69 transport routes** across:

* 🔴 **Nadeem Transport**
* 🟡 **Jadoon Transport**

Each route contains:

* 🚌 Route number
* 👨‍✈️ Driver name
* 📞 Driver phone number
* 📍 Complete stop list
* ⏱️ Stop timings
* 🏁 FAST arrival time

### 🧊 Interactive Route Cards

Each route card provides:

* Expandable stop list
* Highlighted arrival time
* Live departure countdown
* Driver contact
* Google Maps navigation
* Call Driver
* Notify Me
* Share Route
* Favorite route
* Compare route

---

# 🔎 Smart Search & Filtering

Find transport information instantly.

### Search By

* 🔢 Route number
* 👨‍✈️ Driver name
* 📍 Stop name
* 🏙️ Area

Search results update in real time.

### 🎛️ Filters

```text
🔴 All Routes
🚌 Nadeem Routes
🟡 Jadoon Routes
📍 Sort by Distance
⭐ Favorites
⇄ Compare
```

### ⌨️ Keyboard Shortcuts

| Shortcut | Action       |
| -------- | ------------ |
| `/`      | Focus search |
| `Esc`    | Clear search |

---

# 📍 GPS & Location Intelligence

The **Use My Location** feature uses browser geolocation to identify nearby transport routes.

After sharing their location, users can see:

* 📍 Nearest routes
* 📏 Distance from pickup points
* 🚶 Walking estimates
* 🚗 Driving estimates
* 🚌 Nearby transport options
* 🔢 Routes ranked by distance

### 🗺️ Nearby Routes

A dedicated **Routes Near You** section displays nearby routes with:

* Distance badges
* Quick-jump buttons
* Route information
* Distance-based sorting

The application includes approximate coordinate mapping for approximately **80 Karachi areas**, combined with jittered per-stop coordinates for realistic distance calculations.

---

# 🗺️ Google Maps Integration

Every route includes an **Open in Google Maps** button.

The application automatically generates a multi-stop driving route using:

* Starting pickup point
* Route stops
* Waypoints
* Destination

This makes it easier for students to understand the actual route path.

---

# ⏱️ Live Departure Countdown

Every route card displays a live departure countdown.

Example:

```text
🚌 DEPARTS IN 2h 15m
```

Countdowns automatically refresh every **20 seconds**.

### 🚦 Visual Urgency States

🟢 **Upcoming**

🟡 **Departing Soon**

🟠 **Very Soon**

🔴 **Departure Alert**

---

# ⭐ Personalization

The application remembers user preferences through browser `localStorage`.

## ⭐ Favorites

Star frequently used routes and access them through the dedicated **Favorites** section.

## 📌 My Route

Pin your most frequently used route.

A sticky banner displays:

```text
📌 MY ROUTE
Next Departure: 6:45 AM
```

## 🕒 Recently Viewed

Automatically tracks the user's **last 6 viewed routes**.

## 💾 Persistent Data

The following information persists between sessions:

* Favorites
* Pinned route
* Recently viewed routes
* Theme preference

---

# 🔔 Notifications

## Notify Me

Users can enable a browser notification for a route departure.

The system is designed to notify users approximately:

> 🟣 **10 minutes before departure**

This eliminates the need to repeatedly check route timings.

---

# 📤 Route Sharing

Share complete route information directly from any route card.

### Available Sharing Methods

🟢 **WhatsApp**

📱 **Native Share Sheet**

📋 **Copy to Clipboard**

Shared information can include:

* Route number
* Driver
* Phone number
* Stops
* Timings
* Arrival information

---

# ⇄ Route Comparison

Compare up to **3 routes simultaneously**.

### Comparison Includes

| Information        | Available |
| ------------------ | :-------: |
| 🚌 Route Number    |     ✅     |
| 👨‍✈️ Driver       |     ✅     |
| 📞 Phone           |     ✅     |
| 📍 Stop Count      |     ✅     |
| 🟢 First Stop      |     ✅     |
| 🔴 Last Stop       |     ✅     |
| 🗺️ Full Stop List |     ✅     |

A floating comparison bar displays the current selection count.

---

# 📞 Quick Actions

Every route card provides instant actions.

### 📞 Call Driver

Uses the device's `tel:` functionality to contact the driver.

### 🔔 Notify Me

Creates a departure reminder.

### 📤 Share

Shares complete route information.

### 🗺️ Google Maps

Opens the route in Google Maps with multiple stops and waypoints.

---

# 🤖 AI Route Assistant

The **AI Route Assistant** is one of the main features of the project.

Students can ask questions naturally instead of manually searching through route cards.

### 💬 Example Questions

```text
Which route goes through Malir?

What's the phone number for Route 12?

What time does Route 5 depart?

Show me the stops for Route 28.

What's the nearest stop to me?

What's the nearest stop to Gulshan?

What's the next bus?

Mausam kaisa hai?
```

The assistant supports:

* 🇬🇧 English
* 🇵🇰 Urdu-mix queries

---

## 🧠 AI Capabilities

The assistant understands:

* 🚌 Route lookups
* 📞 Driver phone numbers
* 📍 Stop lists
* ⏱️ Route timings
* 📌 Nearest stop queries
* 🏙️ Area-based route searches
* 🚌 Next bus queries
* 🌤️ Live weather
* 💬 General transport assistance

---

## 🔎 Fuzzy Driver Matching

Minor spelling mistakes in driver names can still be matched against available drivers.

This makes driver searches more forgiving.

---

## ⚡ Inline AI Actions

AI responses can provide contextual actions such as:

* 📋 Copy phone
* 📞 Call driver
* 🚌 Jump to route
* 📍 Find route

---

## 💡 Quick Reply Chips

The chat interface provides suggested questions for common transport actions.

Users can tap a suggestion instead of typing manually.

---

# 🎤 Voice Assistant

The AI Route Assistant also supports voice interaction.

### 🎤 Voice Input

Use the microphone to convert speech into text.

### 🔊 Voice Replies

The assistant can read responses aloud using text-to-speech.

Both features are toggleable.

---

# 🌤️ Live Weather

The application displays real-time **Karachi weather** using the **Open-Meteo API**.

Weather information is available:

* 🌤️ In the hero statistics card
* 🤖 Through the AI Assistant

### 🛡️ Reliability

The weather system includes:

* Retry handling
* Request timeout
* Stale-cache fallback

This helps prevent temporary API problems from disrupting the experience.

---

# 🎨 Futuristic UI

The interface uses a colorful **transport HUD / futuristic dashboard aesthetic**.

### 🎨 Main Accent Palette

| Color     | Purpose                            |
| --------- | ---------------------------------- |
| 🔴 Red    | Primary transport actions          |
| 🟡 Gold   | Highlights & important information |
| 🔵 Cyan   | AI & futuristic elements           |
| 🔵 Blue   | GPS & weather                      |
| 🟣 Purple | Notifications & personalization    |
| 🟢 Green  | Live / active states               |
| 🟠 Orange | Warnings & urgency                 |
| ⚫ Dark    | HUD / futuristic foundation        |

---

# 🌙 Dark & Light Themes

Includes:

* 🌑 Dark Mode
* ☀️ Light Mode
* Animated theme toggle
* Persistent preference
* Full color-scheme adaptation

Theme preference is saved using `localStorage`.

---

# 🚪 Animated Boot Sequence

The website opens with a cinematic transport-inspired boot sequence featuring:

* 🚪 Sliding metal doors
* 🖥️ HUD status text
* 📊 Animated progress bar
* 🚌 Driving bus icon
* 🔘 Node-by-node loading indicators
* 🔊 Synchronized sound effects
* 🎵 Optional background music

### 🔊 Audio Policy

Background music **never autoplays**.

The user must explicitly tap to enable it.

---

# ✨ Particle Network Background

An animated HTML Canvas particle network creates a dynamic background.

The system reacts to the selected theme.

---

# 🖱️ Custom Cursor

Desktop users get a custom cursor system featuring:

* Dot cursor
* Trailing ring
* Hover states
* Cursor-following glow
* Interactive reactions

---

# 🧊 3D Route Cards

Route cards provide an interactive 3D HUD experience.

### Effects

* 3D tilt-on-hover
* Neon glow borders
* HUD corner brackets
* Scanning bus animation
* Dynamic glow effects

---

# 🚌 Animated Hero Section

The hero section includes:

* Mouse-based 3D tilt
* Scroll-based parallax
* Scale/fade transitions
* Animated bus
* Dashed road lane
* 🔴 **LIVE ROUTE TRACKING** badge
* Pulsing live indicator

---

# 🎬 Scroll & Navigation Effects

The application includes:

* Scroll-reveal route cards
* Header shrink-on-scroll
* Header sheen animation
* Smooth transitions
* Hover animations
* Interactive feedback

---

# 🔊 Sound & Tactile Interaction

Buttons and links use synthesized **Web Audio API** effects.

No external sound files are required for button interaction sounds.

Buttons also feature:

```text
PRESS
  ↓
FEEDBACK
  ↓
RELEASE
```

creating a tactile interface experience.

---

# 📊 Live Statistics

The dashboard includes animated count-up statistics for:

* 🚌 Total routes
* 👨‍✈️ Total drivers
* 📍 Unique stops
* ⏱️ Arrival information

---

# 🕐 Live Clock

A live digital clock is displayed in the header and updates dynamically.

---

# 📱 Responsive Design

The interface is optimized for:

* 🖥️ Desktop
* 💻 Laptop
* 📲 Tablet
* 📱 Mobile

The navigation, route cards, filters, comparison system, and AI assistant adapt to smaller screens.

---

# 🛠️ Tech Stack

## 🎨 Frontend

* HTML5
* CSS3
* Vanilla JavaScript

## 🌐 Browser APIs

* Geolocation API
* Web Notifications API
* Web Share API
* Clipboard API
* Web Speech API
* Web Audio API
* HTML5 Canvas
* LocalStorage

## 🌤️ External APIs

* Open-Meteo API

## 🗺️ Maps

* Google Maps URL integration

## 🚀 Deployment

* Vercel

---

# 📂 Project Structure

```text
FAST-Transport-System/
│
├── index.html
├── README.md
│
├── assets/
│
└── screenshots/
```

> The exact structure may vary depending on the current project version.

---

# 🚀 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/s0mil/Fast-Transport-System.git
```

### 2️⃣ Enter the Project

```bash
cd Fast-Transport-System
```

### 3️⃣ Run the Website

Open:

```text
index.html
```

in your browser.

For development, **VS Code Live Server** is recommended.

---

# 🌐 Live Deployment

<p align="center">

### 🚀 FAST TRANSPORT SYSTEM

**https://fasttransport.vercel.app/**

</p>

---

# 🎯 Project Goal

Students often have to search through lengthy transport documents just to answer simple questions:

> 🚌 Which bus goes through my area?

> 📍 Where is my nearest pickup point?

> ⏱️ What time does my bus leave?

> 📞 What's my driver's number?

FAST Transport System turns that process into a few seconds.

### 📄 Traditional Method

```text
📄 PDF
   ↓
🔍 Search
   ↓
🚌 Find Route
   ↓
📍 Find Stop
   ↓
⏱️ Check Timing
```

### 🚍 FAST Transport System

```text
🔍 Search / 🤖 Ask AI
          ↓
       🚌 Route
          ↓
   📍 Stop + ⏱️ Time
```

---

# 🔮 Future Possibilities

Potential future improvements include:

* 🛰️ Real-time GPS bus tracking
* 📍 Live bus locations
* 👤 Student accounts
* 🛠️ Admin dashboard
* 📲 Progressive Web App
* 🔔 Advanced personalized notifications
* 🚌 Live bus occupancy
* 📈 Transport analytics
* ☁️ Cloud-based route management
* 🔄 Automatic route updates
* 🏫 Multi-campus support

---

# 👨‍💻 Developer

## Somil

**Computer Science Student — FAST-NUCES Karachi**

Built to make daily transport information easier and faster for fellow FASTians.

### 🐙 GitHub

**https://github.com/s0mil**

### 💼 LinkedIn

**https://www.linkedin.com/in/s0mil/**

---

# ⭐ Support the Project

If you find **FAST Transport System** useful, consider giving the repository a ⭐.

Every star helps support the project and motivates further development.

---

<div align="center">

# 🔴🟡🔵🟣🟢 FAST TRANSPORT SYSTEM 🚌

### **Find Your Route. Catch Your Bus. Get to FAST.**

**Made with ❤️ by Somil**

</div>
