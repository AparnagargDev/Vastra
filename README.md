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

cd client
npm install

cd server
npm install

3️⃣ Run the Application

🔧 Start Backend:

nodemon server


💻 Start Frontend:

npm start


Now, open http://localhost:3000
 in your browser.

🌱 Future Improvements

✅ Add JWT-based secure authentication

✅ Add product reviews and ratings

📊 Build admin dashboard with analytics

📦 Add inventory management & stock tracking

🔔 Email Notifications for Order Updates

🤝 Contributing

Pull requests are welcome!
For major changes, please open an issue first to discuss what you would like to change.

📃 License

This project is licensed under the MIT License.

