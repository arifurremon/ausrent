# 🏠 AusRent — Real Estate Listings Platform

> **Status: 🚧 In Active Development**

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-View_Project-0EA5E9?style=for-the-badge)](https://arifurremon.github.io/ausrent/ausrent-3d.html)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)](https://github.com/arifurremon/ausrent)

## 🌐 [**→ View Live Interactive Demo ←**](https://arifurremon.github.io/ausrent/ausrent-3d.html)

---

A full-stack real estate listings platform that allows users to search, browse, and explore properties with an interactive map interface.

---

## Table of Contents

- [About](#about)
- [Live Demo](#-live-demo)
- [Tech Stack](#-tech-stack)
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Environment Variables](#-environment-variables)
- [Run the App](#-run-the-app)
- [Development & Contributing](#-development--contributing)
- [Roadmap](#-roadmap)
- [Author & Contact](#-author--contact)
- [License](#-license)

---

## About

AusRent is a full-stack real estate listings platform built to provide an interactive, map-first browsing experience for property seekers. It includes a React + TypeScript frontend, a Node.js + Express backend, and PostgreSQL database with Mapbox integration for location-based property search.

---

## 🌐 Live Demo

**[👉 Click here to view the interactive showcase →](https://arifurremon.github.io/ausrent/ausrent-3d.html)**

This page features:
- 3D floating property card with interactive animations
- Particle background effects
- Project overview and tech stack showcase
- Interactive feature highlights
- Certifications and author information

---

## 🖥️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React, TypeScript, Vite |
| Backend | Node.js, Express.js |
| Database | PostgreSQL |
| Maps | Mapbox API |
| Version Control | Git / GitHub |
| Hosting | GitHub Pages |

---

## ✨ Features

- 🗺️ **Interactive Map Search** — Browse properties visually using Mapbox integration
- 🔍 **Property Listings** — Search, filter, and sort real estate listings
- 📱 **Responsive Design** — Mobile-first and responsive layouts
- 🔗 **RESTful API** — Clean backend endpoints for properties management
- 🛡️ **Input Validation** — Server-side validation and error handling
- ✨ **Interactive UI** — Smooth animations and 3D effects

---

## 📁 Project Structure

```
ausrent/
├── client/                    # React + TypeScript frontend (Vite)
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── ...
├── server/                    # Node.js + Express backend
│   ├── routes/
│   ├── controllers/
│   └── ...
├── ausrent-3d.html           # Interactive showcase page
├── README.md
└── LICENSE
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js v18+
- PostgreSQL
- Mapbox API Key

### Installation

```bash
# Clone the repository
git clone https://github.com/arifurremon/ausrent.git
cd ausrent

# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install
```

---

## 🧩 Environment Variables

Create a `.env` file in `/server`:

```
DATABASE_URL=postgresql://user:password@localhost:5432/ausrent_db
PORT=5000
```

Create a `.env` file in `/client`:

```
VITE_MAPBOX_TOKEN=your_mapbox_api_key
```

**Notes:**
- Keep sensitive values out of version control
- For local development with PostgreSQL, ensure the database and user exist
- Set DATABASE_URL accordingly

---

## ▶️ Run the App

**Start the backend** (in `/server` folder):

```bash
cd server
npm run dev
```

**Start the frontend** (in a new terminal):

```bash
cd client
npm run dev
```

**View the live demo:** https://arifurremon.github.io/ausrent/ausrent-3d.html

---

## 🛠 Development & Contributing

Contributions are welcome! Here's how to contribute:

1. **Fork** the repository and create a feature branch:
   ```bash
   git checkout -b feat/my-feature
   ```

2. **Install dependencies** and run the app locally

3. **Make your changes** and test thoroughly

4. **Open a pull request** describing your changes

**Issues & Requests:**
- Open issues for bugs or feature requests
- Comment on issues before starting work
- Assign yourself to issues you're working on

---

## 📅 Roadmap

Planned improvements:

- 🔐 Authentication (user accounts, saved searches)
- 🔍 Advanced filtering and pagination
- 📍 Server-side geospatial queries (PostGIS)
- ✅ Unit/integration tests for API and UI
- 📊 Property analytics dashboard

---

## 🏆 Certifications

- **HackerRank** — Software Engineer Intern (Role Certification)
- **HackerRank** — SQL (Advanced)
- **HackerRank** — Problem Solving (Intermediate)
- **HackerRank** — Java (Basic)

---

## 👨‍💻 Author & Contact

**Arifur Rahman**

- **GitHub:** [@arifurremon](https://github.com/arifurremon)
- **LinkedIn:** [arifur-rahman-emon](https://www.linkedin.com/in/arifur-rahman-emon-0792953ab)
- **Email:** arifurrahman8121@gmail.com

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Made with ❤️ by Arifur Rahman**
