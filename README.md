# Construction Management System (CMS)

A comprehensive web-based platform designed to streamline construction project management, including project tracking, workforce management, material procurement, and financial monitoring.

## 🚀 Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** MongoDB (via Mongoose)
- **Frontend:** HTML5, Vanilla CSS, JavaScript
- **Authentication:** JSON Web Tokens (JWT), Bcrypt.js
- **File Uploads:** Multer

## 📂 Folder Structure

```text
CMS/
├── Backend/                # Server-side logic
│   ├── config/             # Database configuration
│   ├── controllers/        # Request handlers
│   ├── middleware/         # Auth & validation middleware
│   ├── models/             # Mongoose schemas
│   ├── routes/             # API endpoints
│   ├── uploads/            # Uploaded files (3D models, reports)
│   ├── utils/              # Helper functions
│   ├── server.js           # Main entry point
│   └── package.json        # Dependencies
├── Frontend/               # Client-side interface
│   ├── admin/              # Admin dashboard pages
│   ├── client/             # Client dashboard pages
│   ├── engineer/           # Engineer dashboard pages
│   ├── worker/             # Worker dashboard pages
│   ├── css/                # Stylesheets
│   ├── js/                 # Application logic
│   └── index.html          # Main login page
└── requirements.txt        # Dependency list (Node.js)
```

## 🛠️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd CMS
   ```

2. **Backend Setup:**
   ```bash
   cd Backend
   npm install
   ```

3. **Environment Variables:**
   Create a `.env` file in the `Backend` directory:
   ```env
   PORT=5500
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

4. **Run the Application:**
   ```bash
   npm start
   ```
   The application will be available at `http://localhost:5500`.

## ✨ Key Features

- **Role-based Dashboards:** Custom views for Admins, Clients, Engineers, and Workers.
- **Project Tracking:** Real-time updates on project progress and milestones.
- **Materials Management:** Inventory and procurement tracking.
- **Attendance & Salary:** Automated attendance logs and salary calculations.
- **Change Requests:** Streamlined process for project modifications.
- **Advanced Analytics:** Data-driven insights into project performance.
- **3D Viewer:** Integrated viewer for architectural designs and 3D models.
