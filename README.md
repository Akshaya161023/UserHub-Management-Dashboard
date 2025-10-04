🧑‍💻 User CRUD Dashboard (React + Redux Toolkit Query)

A responsive User Management Dashboard built using React, Redux Toolkit, and RTK Query.
This project allows you to create, read, update, and delete user data from a REST API endpoint.

------------------------------------------------------------
🚀 Features
------------------------------------------------------------
- Create new users
- View all users in a table
- Edit existing users
- Delete users
- API integration using RTK Query
- State management with Redux Toolkit
- React Router for navigation
- Clean and responsive UI

------------------------------------------------------------
🧩 Tech Stack
------------------------------------------------------------
Frontend: React 18+ (Vite or Create React App)
State Management: Redux Toolkit
Data Fetching: RTK Query
Styling: CSS / Tailwind (if applicable)
API: Beeceptor Mock API

------------------------------------------------------------
🌐 API Endpoint
------------------------------------------------------------
Base URL:
https://ca93c37f40f1bd20f25e.free.beeceptor.com/api/users/

Endpoints:
GET /        - Get all users
GET /:id     - Get a user by ID
POST /       - Create a new user
PUT /:id     - Update an existing user
DELETE /:id  - Delete a user

------------------------------------------------------------
⚙️ Installation & Setup
------------------------------------------------------------
1. Clone the repository
   git clone https://github.com/<your-username>/user-crud-dashboard.git
   cd user-crud-dashboard

2. Install dependencies
   npm install

3. Start the development server
   npm run dev

4. Open in browser
   http://localhost:5173

------------------------------------------------------------
🧠 Project Structure
------------------------------------------------------------
user-crud-dashboard/
│
├── src/
│   ├── app/
│   │   └── store.js
│   ├── features/
│   │   └── users/
│   │       ├── userApi.js
│   │       ├── userSlice.js
│   │       └── UserList.jsx
│   ├── components/
│   │   ├── AddUserForm.jsx
│   │   ├── EditUserForm.jsx
│   │   └── Navbar.jsx
│   ├── App.jsx
│   └── main.jsx
│
├── package.json
├── README.txt
└── vite.config.js

------------------------------------------------------------
🧪 Example .env (if used)
------------------------------------------------------------
VITE_API_BASE_URL=https://ca93c37f40f1bd20f25e.free.beeceptor.com/api/users/

------------------------------------------------------------
🤝 Contributing
------------------------------------------------------------
1. Fork the repository
2. Create your feature branch (git checkout -b feature-name)
3. Commit your changes (git commit -m 'Add feature')
4. Push to the branch (git push origin feature-name)
5. Open a Pull Request

------------------------------------------------------------
📜 License
------------------------------------------------------------
This project is licensed under the MIT License.

------------------------------------------------------------
💬 Author
------------------------------------------------------------
Your Name
GitHub: https://github.com/<your-username>
Email: akshayaachurajan@gmail.com
