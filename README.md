# Task Management System

A full-stack **Task Management Application** built using **React + Vite** (frontend), **Node.js + Express** (backend), and **MongoDB** (database).  
This app allows users to manage tasks and track their performance through analytics and pagination features.

## 🚀 Features

- Create, update, and delete tasks
- View task performance analytics
- Pagination for efficient task loading
- State management using React Context API
- RESTful backend API with Express

## 🛠 Tech Stack

- **Frontend**: React + Vite
- **Backend**: Node.js, Express
- **Database**: MongoDB

## 📂 Project Structure

```
task-management/
├── client/          # Frontend React application
│   └── src/
│       ├── components/
│       ├── context/
│       ├── pages/
│       ├── services/
│       └── utils/
├── server/          # Backend Node.js application
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
├── README.md
└── package.json
```

## 🧩 Getting Started

### Prerequisites

- Node.js (v16+)
- MongoDB
- npm

### Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/ADeshmukh80/task-management.git
cd task-management
```

2. Install client dependencies:

```bash
cd client
npm install
```

3. Install server dependencies:

```bash
cd ../server
npm install
```

4. Create a `.env` file inside `server/` and add:

```plaintext
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

5. Start the backend server:

```bash
cd server
npm run dev
```

6. Start the frontend server:

```bash
cd client
npm run dev
```

7. Access the application at:

```
http://localhost:5173
```

## 📈 Future Enhancements

- User authentication (Login/Signup)
- Search, filter, and sort tasks
- Real-time updates using WebSocket
- Better UI/UX improvements

## 🤝 Contributing

Contributions are welcome! Please open an issue or pull request.

## Screenshots

![WhatsApp Image 2025-04-28 at 12 46 35_d4aadeee](https://github.com/user-attachments/assets/5750ef95-b1ca-455c-8850-67a71b6af94c)
![WhatsApp Image 2025-04-28 at 12 46 35_eff45008](https://github.com/user-attachments/assets/5d51cd33-b391-4591-8009-041004472b6b)


## 📄 License

This project is licensed under the [MIT License](LICENSE).
