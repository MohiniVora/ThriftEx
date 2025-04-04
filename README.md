# 🛍️ ThriftEx

ThriftEx is a full-stack e-commerce platform for buying and selling preowned clothing. It includes features for both buyers and sellers, supports price negotiation, and integrates shipping and payment APIs for a smooth end-to-end experience.

---

## 🚀 Features

### 👤 User Roles
- **Buyer**: Browse listings, make offers, track orders, and manage cart/wishlist.
- **Seller**: Manage products, view analytics, handle negotiations, and track shipments.
- **Admin**: Oversee the entire system, manage users, orders, and complaints.

### 🛒 Buyer Features
- Product search & filters  
- Add to cart and wishlist  
- Price negotiation with sellers  
- Secure checkout with Razorpay  
- Track orders and view order history  

### 📈 Seller Dashboard
- Add/update product listings  
- Accept/reject/counter offers  
- View analytics: sales, listings, revenue  
- Update order tracking status  
- Restock sold items  

### 🛠️ Admin Dashboard
- Review complaints  
- View total revenue  
- View total buyers & sellers  
- View product count  
- Manage all orders  

### 🔄 Key Integrations
- **Shippo API**: Shipping label generation, rate calculations, order tracking  
- **Razorpay**: Secure payments  
- **Cloudinary**: Image uploads with AI tagging and moderation (optional)  

### 🔐 Authentication & Session Management
- Session-based login for buyers, sellers, and admins  
- Protected routes with session checks  
- Session destroyed upon logout with back-navigation prevention  

---

## 🧰 Tech Stack

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Node.js, Express.js  
- **Database**: SQL (MySQL/PostgreSQL)  
- **Templating**: EJS or Razor (based on project structure)  
- **APIs**: Razorpay, Shippo, Cloudinary (optional)  

---

## 📦 Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/MohiniVora/ThriftEx.git
cd ThriftEx


2️⃣ Install Dependencies
bash
Copy
Edit
npm install express dotenv path ejs mysql2 express-session connect-session-sequelize razorpay shippo multer cloudinary body-parser cookie-parser
📝 If you use PostgreSQL, replace mysql2 with pg

For development:

bash
Copy
Edit
npm install --save-dev nodemon

3️⃣ Create a .env File
env
Copy
Edit
PORT=3000
DB_HOST=localhost
DB_USER=root
DB_PASS=yourpassword
DB_NAME=thriftex

CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

SESSION_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

SHIPPO_API_KEY=your_shippo_key

RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_KEY_SECRET=your_razorpay_secret


4️⃣ Start the App
bash
Copy
Edit
npm start


5️⃣ Or Run Directly
bash
Copy
Edit
node app.js
📸 Screenshots
(Add screenshot images inside a screenshots/ folder and link them below)

markdown
Copy
Edit
### 🛍️ Buyer Dashboard
![Buyer Dashboard](./screenshots/buyer-dashboard.png)

### 📈 Seller Analytics
![Seller Dashboard](./screenshots/seller-dashboard.png)

### 🧾 Admin Panel
![Admin Dashboard](./screenshots/admin-dashboard.png)
✨ Future Improvements
Mobile responsiveness

Admin analytics dashboard

Email/SMS notifications

User reviews and ratings

🙌 Acknowledgments
Shippo

Razorpay

Cloudinary

Made with 💚 by Mohini Vora & Insiya Arsiwala 

yaml
Copy
Edit

---

Let me know if you'd like me to:
- Automatically save this to a file (e.g., `README.md`)
- Help add actual screenshot images
- Customize this further for deployment or a portfolio showcase page






