# EcomStore - A Complete Frontend E-commerce Project

This project is a complete frontend for an e-commerce store built primarily with HTML, CSS, and JavaScript, utilizing Bootstrap 5 for responsive design. The project simulates a full user experience for an online store, from browsing products to completing the checkout process.

[Insert a project screenshot here - you can take a screenshot of the homepage]

---

## ✨ Key Features

- **Complete Authentication System:**
  - Supports three user roles: **Customer**, **Seller**, and **Admin**.
  - Includes a "backdoor" login for the admin (`admin@ecom.com`).

- **Dynamic Product Pages:**
  - **Homepage:** Features a professional slider and a "Featured Products" section.
  - **All Products Page:** Displays all products with interactive filters for searching by name, category, and sorting by price.
  - **Product Details Page:** A dedicated page for each product showing its full details, a mini image gallery, and related products.

- **Full Shopping Experience:**
  - **Shopping Cart:** Fully dynamic, allowing users to adjust quantities and remove items.
  - **Multi-Step Checkout Process:** Starts with a Shipping page and proceeds to a Payment page, with form validation.
  - **Order Persistence:** After a successful payment, the order is saved to `localStorage` to be displayed on the user's "My Orders" page.

- **User Dashboards:**
  - **User Profile Page:** A professional design that allows users to update their information, featuring an avatar generated from their initials.
  - **My Orders Page:** Displays a history of all the user's past orders and their details.
  - **Admin Panel:** Shows statistics for total users and products, with tables for managing users and products.

- **Enhanced User Experience (UX):**
  - **Smart Navbar:** Dynamically changes to show relevant links (Profile, Cart, Seller/Admin Dashboard, Logout) based on the user's login status and role.
  - **Real-time Cart Icon:** The number on the cart icon updates instantly.
  - **Responsive Design:** The website works perfectly on all screen sizes, from mobile to desktop, featuring an Offcanvas menu for mobile.

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
- **JavaScript (ES6+)**
- **Bootstrap 5**
- **Font Awesome** (for icons)

---

## 🚀 Getting Started

This is a frontend-only project and does not require complex installations.

1.  Clone the repository to your local machine:
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```
2.  Open the project folder.
3.  Open the `index.html` file in your browser (preferably using a Live Server in VS Code).

---

## 📂 Project Structure


/ ├── assets/ │ ├── css/ (CSS Files) │ ├── js/ (Main JavaScript Files) │ └── imgs/ (Static Images) ├── auth/ │ ├── signin/ │ ├── signup/ │ └── profile/ ├── cart/ ├── checkout/ ├── orders/ ├── product-details/ ├── products/ ├── admin/ └── index.html (Homepage)


---

## 👤 Author

**Ahmed Hussein**

- **GitHub:** [@medo-hussein](https://github.com/medo-hussein)
- **Email:** medoh745.ah@gmail.com
