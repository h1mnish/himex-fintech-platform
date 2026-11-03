# HIMEX — Finance, Simplified.

<img width="1440" height="665" alt="Screenshot 2026-11-03 200827" src="https://github.com/user-attachments/assets/b25d2c2e-b888-4715-88e0-02109e5c9511" />

<img width="1385" height="667" alt="Screenshot 2026-11-03 201339" src="https://github.com/user-attachments/assets/8f4d8b26-e140-4fff-9424-d5085cda6b2d" />


<img width="1312" height="713" alt="Screenshot 2026-11-03 201707" src="https://github.com/user-attachments/assets/5462aae7-9295-4653-b641-23f871c6c7ae" />


## Overview

**HIMEX** is a modern fintech web application designed to provide a unified financial experience through an intuitive interface and a structured full-stack architecture.

The platform combines a professional marketing website with an investment dashboard, enabling users to explore financial information, manage portfolios, track orders, and interact with financial data.

Built using the MERN stack, HIMEX demonstrates modern frontend development, backend API integration, database management, and authentication workflows.

## ✨ Key Features

- **Modern Landing Page** — Professional fintech website with responsive layouts.
- **Investment Dashboard** — Centralized financial dashboard.
- **Portfolio Management** — View holdings and positions.
- **Order Management** — Manage and track buy/sell orders.
- **Watchlist** — Explore and interact with listed stocks.
- **Financial Analytics** — Visual representation of portfolio data.
- **Secure Authentication** — JWT-based login and registration.
- **Dark & Light Themes** — Persistent theme preferences.
- **Responsive Interface** — Optimized for desktop, tablet, and mobile.

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| Frontend | React, React Router, Bootstrap |
| Dashboard | React, Material UI, Chart.js |
| Backend | Node.js, Express.js |
| Database | MongoDB, Mongoose |
| Authentication | JWT, bcryptjs |
| API Communication | Axios, REST APIs |
| Development | npm, nodemon |
| Deployment | Render |

## 🏗️ Architecture

HIMEX follows a three-tier architecture.

```text
                 HIMEX PLATFORM
                       |
          +------------+------------+
          |                         |
     Frontend                  Dashboard
     React App                 React App
          |                         |
          +------------+------------+
                       |
                  REST API
                 Express.js
                       |
                   MongoDB
```

### Application Structure

| Application | Port | Responsibility |
|---|---:|---|
| Frontend | 3000 | Landing page, authentication, marketing |
| Dashboard | 3001 | Investment dashboard and portfolio |
| Backend | 4000 | REST API, authentication and database |

## 📂 Project Structure

```text
himex-fintech-platform/
│
├── frontend/
│   ├── public/
│   └── src/
│       ├── landing_page/
│       ├── theme/
│       └── App.js
│
├── dashboard/
│   ├── public/
│   └── src/
│       ├── components/
│       ├── theme/
│       └── data/
│
├── backend/
│   ├── middleware/
│   ├── model/
│   ├── schemas/
│   ├── util/
│   └── index.js
│
├── docs/
│   └── screenshots/
│       ├── himex-homepage.png
│       ├── himex-features.png
│       └── himex-pricing.png
│
└── README.md
```

## 🔐 Authentication & Security

- JWT-based authentication.
- Password hashing using bcryptjs.
- Protected API routes.
- Bearer token authorization.
- User-scoped order management.
- Environment-based secret configuration.

## ⚙️ Installation & Setup

### Prerequisites

- Node.js 18+
- npm 9+
- MongoDB Atlas account or local MongoDB

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/himex-fintech-platform.git

cd himex-fintech-platform
```

### 2. Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file inside the backend directory:

```env
MONGO_URL=your_mongodb_connection_string
TOKEN_KEY=your_jwt_secret
PORT=4000
```

Start the backend:

```bash
npm start
```

### 3. Frontend Setup

Open another terminal:

```bash
cd frontend
npm install
npm start
```

Frontend runs at:

`http://localhost:3000`

### 4. Dashboard Setup

Open another terminal:

```bash
cd dashboard
npm install
npm start
```

Dashboard runs at:

`http://localhost:3001`

## 🚀 Future Improvements

- Real-time financial data integration.
- Advanced portfolio analytics.
- Improved transaction management.
- WebSocket-based live updates.
- AI-powered financial insights.
- Enhanced security and performance.
- Cloud infrastructure improvements.


## 👨‍💻 Author

**Himnish Tyagi**

Computer Science & Engineering

GitHub: https://github.com/h1mnish
