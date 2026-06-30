# Film Review Database and Interface

A full-stack web application designed to store, manage, and query a comprehensive film review database. Built using a **React** frontend, a **Node.js/Express** backend API, and a **Relational SQL Database** to process complex relational film schemas, actor links, and user reviews.

---

## Features

- **Film Discovery & Cataloging:** Browse movies with mapped movie poster assets.
- **Comprehensive Schema Relationships:** Handles relations across movies, directors, genres, actors, and user reviews natively through relational constraints.
- **Dynamic Review Engine:** Add, update, or read user reviews with seamless database syncing.
- **Pre-configured Database Setup:** Includes a `dbsample.sql` schema script to rapidly populate sample movie assets, schemas, and review metrics.

---

## Tech Stack

- **Frontend:** React.js, HTML5, CSS3
- **Backend:** Node.js, Express.js
- **Database:** SQL (PostgreSQL / MySQL compatible)
- **Asset Storage:** Local static asset infrastructure for movie posters

---

## Project Structure

```text
├── backend/               # Express server, API routes, and relational database integrations
├── frontend2/             # React SPA (State management, interactive views, and layout)
├── posters_for_movie/     # Local storage directory holding movie poster image assets
├── dbsample.sql           # Database initialization schema containing tables and sample data records
├── package.json           # Application dependency manifests
└── README.md              # Project Documentation
