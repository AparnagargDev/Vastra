# 🛍️ Vastra - E-Commerce Platform (MERN Stack)

**Vastra** is a modern full-stack e-commerce platform where users can browse products, manage carts, and place orders — while admins manage the catalog, orders, and users through a secure dashboard. It provides a seamless shopping experience with a clean and responsive UI.

---

## ✨ Key Features

### 👤 User Side
- ✅ User Registration & Login  
- 🔐 Change Password Functionality  
- 🔎 Product Search by Keyword  
- 🛒 Add to Cart & Place Orders  
- 🧾 View Order History  
- 🧱 Route Protection for Authenticated Users  
- 🚫 Cart & Order access restricted to logged-in users  
- 📱 Fully Responsive Design  

### 🛠️ Admin Panel

🚨 **DEMO ADMIN LOGIN (FOR QUICK ACCESS):**  
Email: admin@gmail.com
Password: 1234

yaml
Copy code

- 🧑‍💻 Secure Admin Login (Role-Based)  
- 📦 Manage Categories & Subcategories  
- ➕ Add, Update, Delete Products  
- 📷 Upload Product Images via Cloudinary  
- 🔎 Search & Manage Users  
- 📊 View & Filter All Orders  
- 🔄 Update Order Status (Pending → Shipped → Delivered)  
- 🧾 View Order Details with Product Breakdown  
- 🔒 All Admin Routes Fully Protected  

---

## 🧠 Extra Highlights
- 💳 Checkout Flow with Order Tracking  
- 🌐 REST API Integration between Frontend & Backend  
- 🛒 Persistent Cart using React State  
- ✨ Smooth UI/UX with Bootstrap styling  
- 🧩 Modular Folder Structure for Clean Scalability  

---

## 🧑‍💻 Tech Stack

| Layer       | Technology          |
|-------------|---------------------|
| Frontend    | HTML, CSS, Bootstrap, React.js |
| Backend     | Node.js, Express.js |
| Database    | MongoDB Atlas       |
| Auth        | Basic Auth (Session-based) |
| State Mgmt  | React State         |
| Cloud       | Cloudinary (for images) |

---

## 🗂️ Project Structure
Vastra/
├── client/
│ ├── public/
│ ├── src/
│ │ ├── Components/
│ │ ├── App.css
│ │ ├── App.js
│ │ ├── index.js
│ │ ├── ...
│ ├── package.json
│
├── server/
│ ├── public/
│ ├── server.js
│ ├── package.json
│ ├── ...
│
├── .gitignore
└── README.md

---

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/AparnagargDev/Vastra.git
cd Vastra
2️⃣ Install Dependencies
For both client and server (run in separate terminals):

bash
Copy code
# Frontend
cd client
npm install

# Backend
cd server
npm install
3️⃣ Setup Environment Variables
Backend (server/.env)
ini
Copy code
MONGO_URI=<Your MongoDB Atlas Connection String>
CLOUDINARY_CLOUD_NAME=<Your Cloudinary Cloud Name>
CLOUDINARY_API_KEY=<Your Cloudinary API Key>
CLOUDINARY_API_SECRET=<Your Cloudinary API Secret>
PORT=9000   # Or any port you prefer
Frontend (client/.env)
ini
Copy code
REACT_APP_API_URL=<Your Backend URL>
# Examples:
# Local: http://localhost:9000
# Render Deployment: https://vastra-k3gh.onrender.com
4️⃣ Run the Application
🔧 Start Backend
bash
Copy code
cd server
nodemon server
💻 Start Frontend
bash
Copy code
cd client
npm start

Open your app in the browser:

- Local: [http://localhost:3000](http://localhost:3000)  
- Live Frontend: [https://vastra-mocha.vercel.app/](https://vastra-mocha.vercel.app/)  
## 🌱 Future Improvements

- ✅ Add JWT-based secure authentication  
- ✅ Add product reviews and ratings  
- 📊 Build admin dashboard with analytics  
- 📦 Add inventory management & stock tracking  
- 🔔 Email Notifications for Order Updates  
- 💳 Integrate Razorpay for Payment Gateway


