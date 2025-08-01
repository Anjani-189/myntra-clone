# 🛍️ Myntra Clone Web App

This project is a front-end **clone of the Myntra e-commerce website**, built using **React**, **Redux**, **Bootstrap**, and **React Icons**. It is created to practice front-end development with component-based architecture and responsive design principles.

---

## 📁 Project Structure

```bash
myntra-App
├── actual-backend/             # Node.js backend server
│   ├── data/
│   ├── items.json              # Product data (served via Express)
│   ├── app.js                  # Main backend entry
│   ├── package.json
│
└── myntra-react-clone/         # React + Redux frontend
    ├── public/
    ├── src/
    │   ├── components/          # Header, Footer, BagItem, HomeItems, LoadingSpinner, FetchItems
    │   ├── routes/              # Pages: Home, App, Bag
    │   ├── store/               # bagSlice, fetchStatusSlice, itemsSlice
    │   ├── index.css
    │   ├── main.jsx             # React entry file
    ├── package.json
```
---

## 🚀 Features
- ✅ Product listing and detail page
- ✅ Add to cart functionality using Redux
- ✅ Cart page with item count and total price
- ✅ Responsive design using Bootstrap
- ✅ Icons integration via React Icons
- ✅ Component-based structure for clean, modular code

---

## 🛠️ Technologies Used
- React JS
- Redux Toolkit
- React Router DOM
- Bootstrap 5
- React Icons
- JavaScript (ES6+)
- Node.js + Express (for product data)

---
## 📌 How to Use

1. **Clone this repository**  
   ```bash
   git clone https://github.com/Anjani-189/myntra-clone.git
   ```

2. **Navigate to the backend folder and install dependencies**  
   ```bash
   cd actual-backend
   npm install
   ```

3. **Start the backend server**  
   ```bash
   node app.js
   ```
   > This will serve the product data from `items.json` on `http://localhost:8080`.

4. **Open a new terminal and navigate to the frontend folder**  
   ```bash
   cd ../myntra-react-clone
   npm install
   ```

5. **Start the React development server**  
   ```bash
   npm run dev
   ```
   
6. **Visit your app in the browser**  
   Open [http://localhost:5173](http://localhost:5173) to view the Myntra Clone in action.
 ---

 ## 📷 Preview

![Website Preview](screenshot/output.png)

---

## 📚 Learning Purpose
- This project is created only for educational and practice purposes.
- It is not intended for commercial use. All design inspiration belongs to Myntra.com.


