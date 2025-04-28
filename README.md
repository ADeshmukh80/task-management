# Task Management System

A **full-stack Task Management** application built with **React + Vite** on the frontend, **Node.js** on the backend, and **MongoDB** for the database.  
It enables users to manage tasks, track analytics, and monitor productivity in an organized and efficient manner.

## 🚀 Features

- 📋 **Task List**: Create, update, and view tasks.
- 📊 **Task Analytics**: Real-time performance tracking and statistics.
- 🔄 **Update Tasks**: Modify task status, description, and details.
- 📚 **Pagination**: Smooth task loading with page-based navigation.
- 🛠 **Global State Management**: Handled via Context API.
- 🌐 **REST APIs**: Node.js backend APIs for task CRUD operations.
- 🛢️ **MongoDB**: Secure and scalable task storage.

## 🛠 Tech Stack

- **Frontend**: React + Vite, TypeScript, Mantine UI
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (with Mongoose ODM)

## 📂 Project Structure

```
task-management/
├── client/               # Frontend (React + Vite app)
│   ├── src/
│   │   ├── components/
│   │   ├── context/
│   │   ├── hooks/
│   │   ├── pages/
│   │   ├── services/
│   │   └── utils/
│   ├── index.html
│   └── package.json
├── server/               # Backend (Node.js + Express app)
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── config/
│   ├── server.js
│   └── package.json
├── README.md
└── package.json
```

## 📸 Screenshots

> _Screenshots will be added soon showcasing dashboard, analytics, and task operations._

## 🧩 How to Run Locally

### Prerequisites

- Node.js (v16+)
- npm or yarn
- MongoDB instance (local or cloud)

### Setup Instructions

1. **Clone the repository:**

```bash
git clone https://github.com/ADeshmukh80/task-management.git
cd task-management
```

2. **Install dependencies for client and server:**

```bash
cd client
npm install
cd ../server
npm install
```

3. **Set up environment variables for server:**

Create a `.env` file inside the `server/` folder:

```plaintext
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

4. **Start backend server:**

```bash
cd server
npm run dev
```

5. **Start frontend client:**

```bash
cd client
npm run dev
```

6. **Access the app at:**  
[http://localhost:5173](http://localhost:5173)

## 📈 Future Improvements

- User authentication (JWT-based login and signup).
- Task filtering, sorting, and search.
- Real-time updates using WebSockets.
- Role-based access control (admin, user).

## 🤝 Contributing

Contributions and feedback are welcome!  
Please open issues or submit a pull request to improve this project.

## 📄 License

This project is licensed under the [MIT License](LICENSE).
