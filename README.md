
# TwinSync — Smart Habit & Health Score Tracker

TwinSync is a clean and engaging web app that helps users understand their daily lifestyle through a single number: the Health Score. Users can log habits like study time, sleep, work hours, food items, water intake, and social media usage. The app processes these inputs and shows clear analytics, progress, and insights.

Built during VØID:v1 hosted by VIT Chennai, BiC, and technoVIT.

---

## Features

- Track daily routines:
  - Study hours
  - Work hours
  - Social media usage
  - Sleep duration
  - Food intake
  - Water intake
- Smooth, modern UI with Tailwind
- Real-time Health Score calculation
- Secure user authentication
- Local and cloud save options
- Individual dashboards for each user
- Node.js backend with MySQL database
- Simple, responsive UX

---

## Tech Stack

**Frontend**
- React
- Tailwind CSS

**Backend**
- Node.js
- Express.js
- JWT Authentication

**Database**
- MySQL

---

## Folder Structure

```

TWINSYNC/
│
├── client/              # React frontend
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/              # Node.js backend
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   ├── config/
│   └── server.js
│
├── .env.example
├── README.md
└── package.json

````

---

## Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/mrbi10/TWINSYNC
cd TWINSYNC
````

### 2. Backend setup

```bash
cd server
npm install
```

Create a `.env` file:

```
DB_HOST=your_host
DB_USER=your_user
DB_PASS=your_password
DB_NAME=twinsync_db
JWT_SECRET=your_secret
```

Start backend:

```bash
npm start
```

### 3. Frontend setup

```bash
cd ../client
npm install
npm run dev
```

---

## Health Score Logic

The Health Score is calculated using weighted values from:

* Sleep duration
* Water intake
* Study/work balance
* Screen time
* Dietary logs

You can update this section based on your exact formula.

---

## Screenshots

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/52310af1-9a28-49ec-864d-d6683a12610d" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/1a3f84bd-5c32-4e8d-b836-23e5a185e74e" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/f40dd970-676f-4c8b-a0e5-275b0a9d9180" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/0e825529-c4db-4c7f-89af-e5363d8701d5" />


---

## Repository Link

[https://github.com/mrbi10/TWINSYNC](https://github.com/smrithipiedy/TwinSync)

---

## Credits

Built by Team Hashtrix for VØID:v1 at VIT Chennai.
Thanks to Devdock, Smartail, and HCLTech for supporting the event.

```

---


```
