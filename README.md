# 75ways

A full-stack web application built using **React, Node.js, Express.js, and MongoDB**.


Live = https://educonnect-f.onrender.com/

## Tech Stack

* Frontend: React.js
* Backend: Node.js + Express.js
* Database: MongoDB
* API: REST API

## Project Structure

```text
75ways/
├── frontend/
└── backend/
```

## Setup

### 1. Clone Repository

```bash
git clone https://github.com/arpittayal01/Educonnect.git
cd 75ways
```

### 2. Backend

```bash
cd backend
npm install
```

Create `.env`:

```env
MONGO_URL=your_mongodb_connection_string
PORT=5001
```

Run:

```bash
npm start
```

### 3. Frontend

Open another terminal:

```bash
cd frontend
npm install
npm start
```

Frontend runs at:

```text
http://localhost:3000
```

Backend runs at:

```text
http://localhost:5001
```

## Environment Variables

**Backend**

```env
MONGO_URL=your_mongodb_url
PORT=5001
```

**Frontend**

```env
REACT_APP_BASE_URL=your_backend_url
```

## Author

**Arpit Tayal**
GitHub: https://github.com/arpittayal01

