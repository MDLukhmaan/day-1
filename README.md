Absolutely! Here’s **one complete message** you can copy and paste directly as your README.md:

````markdown
# Day 1 – Express + PostgreSQL CRUD API

## 📌 Project Overview
A simple Node.js + Express server connected to PostgreSQL, implementing CRUD APIs for `items`. Tested with Postman.

---

## ⚡ Tech Stack
- Node.js
- Express
- PostgreSQL
- pg (node-postgres)
- dotenv
- cors
- nodemon (dev)

---

## 🚀 Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/MDLukhmaan/day-1.git
````

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env` file in the project root:

```env
PORT=3000
DB_USER=your_user
DB_PASSWORD=your_password
DB_HOST=localhost
DB_PORT=5432
DB_DATABASE=day1db
```

> Use `.env.example` as a reference for your environment variables.

### 4. Run the server

```bash
npm run dev
```

Server runs at → `http://localhost:3000`

---

## 🔑 API Endpoints

### Root

* `GET /` → API is running 🚀

### Items

* `POST /api/items` → create new item
* `GET /api/items` → get all items
* `GET /api/items/:id` → get item by ID
* `PUT /api/items/:id` → update item by ID
* `DELETE /api/items/:id` → delete item by ID

---

## 🧪 Testing with Postman

1. Open Postman
2. Create a Collection → **Day1 API**
3. Add requests:

* `GET /`
* `POST /api/items` (Body → raw → JSON: `{ "name": "Pen", "description": "Blue ink" }`)
* `GET /api/items`
* `GET /api/items/:id`
* `PUT /api/items/:id` (Body → raw → JSON: `{ "name": "Updated Pen", "description": "Black ink" }`)
* `DELETE /api/items/:id`

---

## ✅ Deliverables

* CRUD API working locally
* `.env.example` included
* Public GitHub repo
* Postman screenshots

---

## 🧪 Postman Screenshots

### GET /

!\[GET root]\(![screenshots/Screenshot 2025-09-20 131002.png](<screenshoots/Screenshot 2025-09-20 131002.png>))

### POST /api/items

!\[POST item]\(![screenshots/Screenshot 2025-09-20 131017.png](<screenshoots/Screenshot 2025-09-20 131017.png>))

### GET /api/items/1

!\[GET one item]\(![screenshots/Screenshot 2025-09-20 131205.png](<screenshoots/Screenshot 2025-09-20 131205.png>))

### PUT /api/items/1

!\[Update item]\(![screenshots/Screenshot 2025-09-20 125503.png](<screenshoots/Screenshot 2025-09-20 125503.png>))

### DELETE /api/items/1

!\[Delete item]\(![screenshots/Screenshot 2025-09-20 125554.png](<screenshoots/Screenshot 2025-09-20 125554.png>))

```

---



