# Virtual-fit-clothing-store
Clothing brand website that allows users to make orders, browser collections, view product details, add to cart, try on fits using a virtual model
# 👑 amRoyalty

Welcome to **amRoyalty**, a unique clothing brand that celebrates **individuality, identity, and representation**. At amRoyalty, we believe everyone is royalty — our designs are crafted to empower you to **stand out and confidently express your true self.**

## 🌟 Project Overview

This is the official website for **amRoyalty**, developed to provide our customers with a **seamless, interactive, and personalized shopping experience**. Our platform showcases our distinct fashion pieces and integrates **modern features like:**

- 🧍‍♀️ **Virtual model fitting:** Try on clothes virtually.
- 🎨 **3D imaging:** Visualize products from all angles.
- 🛒 **Smooth shopping experience:** Easy browsing, searching, and purchasing.
- 📱 **Mobile responsiveness:** Perfect shopping on any device.


## 🎯 Project Goals

- Offer a platform that reflects **uniqueness and authenticity**.
- Help customers find pieces that truly represent their **identity**.
- Provide **high-quality visuals and interactive features** for a realistic shopping experience.


## ⚙️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript (with plans to explore modern frameworks)
- **Backend:** Spring Boot (Java)
- **Database:** PostgreSQL
- **APIs:** For managing products, user accounts, virtual fitting, and 3D rendering
## 📌 Key Features

### 🛍️ Customer-Side
- View clothing items (with images, prices, sizes, descriptions)
- Add to cart and place orders
- User registration and login
- View order history
- **Virtual model for trying on outfits**
- **3D interactive view of clothing items**

### 🧑‍💼 Admin-Side
- Add, update, or delete clothing products
- Manage stock levels
- View and process customer orders


### ✅ Frontend
- HTML, CSS, JavaScript *(or React for dynamic UI)*
- 3D rendering with **Three.js** or **Babylon.js** *(optional)*

### ✅ Tools
- Postman (API testing)
- Git + GitHub (version control)
- IntelliJ IDEA or VS Code

## 🗄️ Database Structure (PostgreSQL)

- `Users`: id, name, email, password
- `Products`: id, name, description, price, image_url, size, stock
- `Orders`: id, user_id, total_price, date, status
- `Order_Items`: id, order_id, product_id, quantity

## 🔌 API Endpoints (Examples)

| Method | Endpoint              | Description                |
|--------|-----------------------|----------------------------|
| GET    | `/api/products`       | Get all products           |
| POST   | `/api/users/register` | Register new user          |
| POST   | `/api/orders`         | Place an order             |
| PUT    | `/api/products/{id}`  | Update product info (admin)|


## 🌐 Advanced Features

### 🧍‍♀️ Virtual Model (Try-On)
- Users can create a virtual avatar or select a body type
- Clothes can be previewed on the avatar in real-time
- Integration options: WebAR, virtual fitting SDKs, or WebGL

### 🧥 3D Clothing Visualization
- Rotate, zoom, and inspect clothing in 360°
- Implemented using **Three.js** or similar library
