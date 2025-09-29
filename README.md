# Node API (MongoDB, Express, Node.js)

This project is a simple **REST API** built with:
- **Node.js**
- **Express**
- **MongoDB** (via Mongoose)

It allows you to **create, read, update, and delete (CRUD)** players in a sports team.

---

## Getting Started

### 1. Open Terminal
```bash
cd Node-API
```

### 2. Install dependencies
```bash
npm install
```

### 3. Start MongoDB
Make sure MongoDB is running locally:
```bash
mongod
```

### 4. Run the server
```bash
npm run dev
```
or
```bash
node server.js
```

Server will run at:  
 `http://localhost:3000`

---

##  API Endpoints

### Players
- **POST** `/api/players` → Create a new player  
- **GET** `/api/players` → Get all players  
- **GET** `/api/players/:id` → Get a single player  
- **PATCH** `/api/players/:id` → Update a player  
- **DELETE** `/api/players/:id` → Delete a player  
