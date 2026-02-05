# 🍽️ Treonix — Restaurant Management Website

> **Final-year full-stack project** — a responsive Restaurant Management System with online menu, ordering, table reservations, and an admin dashboard.

---

## 🔖 Short Description

A clean, responsive restaurant website that enables customers to browse the menu, place orders, reserve tables, and track order status. Admins can manage menu items, orders, staff, and reservations via a dedicated control panel.

## 🚀 Features

* Menu browsing with categories and search
* Online ordering (cart, checkout, order status)
* Table reservation system
* Admin dashboard (manage items, orders, users)
* User authentication (register/login)
* Responsive UI for mobile and desktop
* Basic analytics and order history


## 📁 Project Structure (Suggested)

```
/ (root)
├─ packages/
│  ├─ frontend/        # React app (src/, public/, package.json)
│  ├─ backend/         # Node/Express API (src/, routes/, models/)
│  └─ ai-service/      # optional LLM or helper microservice
├─ infra/              # docker-compose, k8s manifests
├─ docs/               # architecture, ER diagrams, API docs
├─ scripts/            # db seeds, migrations
├─ README.md
└─ .gitignore
```

## ⚙️ Installation (Local)

1. Clone the repo

```bash
git clone https://github.com/Treonix-in/finalyear-restaurant-website.git
cd restaurant-project
```

2. Install dependencies for frontend and backend

```bash
cd packages/frontend && npm install
cd ../backend && npm install
```

3. Create `.env` files (example)

```
# backend/.env
DATABASE_URL=postgres://user:pass@localhost:5432/restaurantdb
JWT_SECRET=your_jwt_secret
```

4. Run services (development)

```bash
# run backend
cd packages/backend && npm run dev
# run frontend
cd ../frontend && npm run dev
```

## 🧪 Tests

* Add unit and integration tests under `packages/*/tests`.
* Run tests per package: `npm test`.

## 🐳 Docker (optional)

A `docker-compose.yml` in `/infra` can spin up the app and a PostgreSQL database for local testing.

## 📸 Screenshots

Place screenshots in `/docs/screenshots` and reference them here:

![Screenshot - Menu](./docs/screenshots/menu.png)


## 📬 Contact

Project maintained by **Treonix** — reach out at `treonixofficial@gmail.com` for collaboration or questions.

---

*Generated README, banner placeholder, and tech stack badges. Update assets/banner.png and docs/screenshots with real images before publishing.*
