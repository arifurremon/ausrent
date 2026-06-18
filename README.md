# 🏠 AusRent — Real Estate Listings Platform

> **Status: 🚧 In Active Development**

A full-stack real estate listings platform that allows users to search, browse, and explore properties with an interactive map interface.

-----

## 🖥️ Tech Stack

|Layer          |Technology         |
|---------------|-------------------|
|Frontend       |React, TypeScript  |
|Backend        |Node.js, Express.js|
|Database       |PostgreSQL         |
|Maps           |Mapbox API         |
|Version Control|Git / GitHub       |

-----

## ✨ Features

- 🗺️ **Interactive Map Search** — Browse properties visually using Mapbox integration
- 🔍 **Property Listings** — Search and filter real estate listings
- 📱 **Responsive Design** — Works across desktop and mobile
- 🔗 **RESTful API** — Clean backend API built with Express.js
- 🗄️ **Relational Database** — Structured property data with PostgreSQL

-----

## 📁 Project Structure

```
ausrent/
├── client/          # React + TypeScript frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── ...
├── server/          # Node.js + Express backend
│   ├── routes/
│   ├── controllers/
│   └── ...
└── README.md
```

-----

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

### Environment Variables

Create a `.env` file in `/server`:

```
DATABASE_URL=your_postgresql_connection_string
PORT=5000
```

Create a `.env` file in `/client`:

```
VITE_MAPBOX_TOKEN=your_mapbox_api_key
```

### Run the App

```bash
# Run backend
cd server && npm run dev

# Run frontend (in a new terminal)
cd client && npm run dev
```

-----

## 👨‍💻 Author

**Arifur Rahman**

- GitHub: [@arifurremon](https://github.com/arifurremon)
- LinkedIn: [arifur-rahman-emon](https://www.linkedin.com/in/arifur-rahman-emon-0792953ab)
- Email: [arifurrahman8121@gmail.com](mailto:arifurrahman8121@gmail.com)

-----

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
