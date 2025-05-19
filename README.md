### 🛍️ Webshop – Copilot Challenge

Build a **webshop solution** using Visual Studio, generated and supported by GitHub Copilot, within 1 hour.

---

### ✅ Objective

Create a Visual Studio solution for a basic webshop with:

* **2 frontend projects**:

  1. **Webshop frontend** – preferably using **Blazor WebAssembly**
  2. **Management tool** – preferably a **Windows Forms** app

---

### 🌐 Webshop Requirements

* A **login page** for customers
* Display a list of **products** on the homepage
* Customers can:

  * Add products to their **shopping cart**
  * View the shopping cart (bubble icon in the top right with product count)
  * The cart **represents the order**
* Orders:

  * Are created automatically when products are added to the cart
  * Contain multiple **order lines**
  * Have a simple **boolean flag** to indicate if they are paid (`IsPaid`)
* No actual payment gateway integration (e.g. Shopify API) is needed
* Customers can view their own orders (cart history)

---

### 🛠️ Management Tool (Windows Forms)

Provide basic **CRUD functionality** for:

* Customers
* Products
* Orders and their OrderLines

---

### 🧩 Data Model (ERD Overview)

* **Customer** → has many **Orders**
* **Order** → has many **OrderLines**
* **OrderLine** → refers to **Product**

Relations:

* `Customer (1) → (n) Order`
* `Order (1) → (n) OrderLine`
* `Product (1) ← (n) OrderLine`

---

### 🕒 Timebox

This task is intended to be completed using GitHub Copilot within **1 hour**, to evaluate its capabilities.
