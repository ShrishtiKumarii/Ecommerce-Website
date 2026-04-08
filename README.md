🛒 Ecommerce Website – Full Stack Project

Welcome to my Full Stack E-commerce Website! This project demonstrates a complete online store built using React for the frontend and Java Spring Boot for the backend.

Whether you want to explore, extend, or use it as a reference, everything is structured cleanly for ease of understanding.

🚀 Features
User Interface (Frontend)
Responsive design with React
Browse products, add to cart, and checkout
Modern, fast-loading UI with intuitive navigation
Backend (Spring Boot)
RESTful APIs for products, cart, and orders
H2 in-memory database for quick setup and testing
Layered architecture: Controllers → Services → Repositories
Extra
Sample products are included in backend/src/main/resources/data1.sql
Fully modular: frontend and backend separated for easy maintenance
🗂️ Project Structure
Ecommerce-Website/
├── frontend/             # React app (UI)
│   ├── public/
│   └── src/
├── backend/              # Spring Boot backend
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/shrishti/ecom_pro/
│   │   │   │   ├── controller/
│   │   │   │   ├── model/
│   │   │   │   ├── repo/
│   │   │   │   └── service/
│   │   │   └── resources/
│   │   │       └── application.properties
│   │   └── test/
│   └── pom.xml
└── README.md
⚡ Quick Start
Backend
cd backend
./mvnw spring-boot:run
Frontend
cd frontend
npm install
npm run dev

Your backend runs at http://localhost:8080 and frontend at http://localhost:5173 (default Vite port).

💡 Notes
H2 database is in-memory, so data will reset when backend restarts.
To persist real data, connect a MySQL/PostgreSQL database and update application.properties.
Fully ready to extend: add authentication, product images, payment gateway, etc.
📸 Preview

(Add screenshots here to make it visually appealing!)

👩‍💻 Tech Stack
Frontend: React, Vite, JavaScript, CSS
Backend: Java Spring Boot, Maven, H2 Database
Version Control: Git & GitHub
