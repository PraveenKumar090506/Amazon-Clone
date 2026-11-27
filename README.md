# 🛒 Amazon Clone

A front-end e-commerce web app inspired by Amazon, built with **vanilla HTML, CSS and JavaScript** — no frameworks. Users can browse products, add them to a cart, check out, view their orders and track deliveries.

I built this project to get hands-on with core JavaScript concepts: **DOM manipulation, callbacks, Promises, async/await and the Fetch API**.

---

## ✨ Features

- **Product listing** — products are loaded dynamically and rendered to the page with JavaScript
- **Shopping cart** — add items, choose quantities, and see the cart count update instantly
- **Checkout page** — review cart items, update or remove them, pick a delivery option and see the order summary (items, shipping, tax, total) recalculate live
- **Place orders** — orders are created and saved so they persist across page reloads
- **Orders page** — view past orders with their products, dates and totals
- **Order tracking** — follow the delivery status of an individual product
- **Responsive layout** — styled to work across different screen sizes

---

## 🧠 What I Learned

| Concept | How it's used in this project |
|---|---|
| **DOM manipulation** | Generating product cards, cart items and order summaries with JavaScript and updating the page without reloading |
| **Event listeners** | Handling clicks for "Add to Cart", "Update", "Delete", delivery options and "Place Order" |
| **Callbacks** | Running code only after data has finished loading |
| **Promises** | Chaining asynchronous steps and loading multiple resources together |
| **async / await** | Writing asynchronous code that reads top-to-bottom, with `try/catch` for errors |
| **Fetch API** | Requesting product data and sending order data to the backend |
| **ES6 Modules** | Splitting code into reusable `import` / `export` files |
| **localStorage** | Keeping the cart and orders saved between visits |

---

## 🛠️ Tech Stack

- **HTML5** — page structure
- **CSS3** — styling and layout
- **JavaScript (ES6+)** — logic, modules, async programming

---

## 📁 Project Structure

```
Amazon-Clone/
├── backend/          # Backend-related files used by fetch requests
├── data/             # Products, cart, orders and delivery option data/logic
├── images/           # Product images, icons and logos
├── scripts/          # Page-specific JavaScript
├── styles/           # CSS files for each page
├── amazon.html       # Home page – product listing
├── checkout.html     # Cart review & checkout
├── orders.html       # Order history
└── tracking.html     # Package tracking
```

---

## 🚀 Getting Started

Because the project uses **ES6 modules and `fetch`**, it needs to be served from a local server (opening the HTML file directly with `file://` won't work).

1. **Clone the repository**
   ```bash
   git clone https://github.com/PraveenKumar090506/Amazon-Clone.git
   cd Amazon-Clone
   ```

2. **Run a local server** (any one option)
   - VS Code: install the **Live Server** extension → right-click `amazon.html` → *Open with Live Server*
   - Node.js:
     ```bash
     npx serve .
     ```
   - Python:
     ```bash
     python -m http.server 5500
     ```

3. **Open in your browser**
   ```
   http://localhost:5500/amazon.html
   ```

---

## 🔮 Future Improvements

- Product search and category filters
- User login and authentication
- Real payment gateway integration
- Unit tests (e.g. Jasmine / Jest)
- Port to React for component-based UI

---

## 🙏 Acknowledgements

This is a learning project. Amazon's name and design are used for educational purposes only — this project is not affiliated with Amazon.

---

## 👤 Author

**Praveen Kumar**
- GitHub: [@PraveenKumar090506](https://github.com/PraveenKumar090506)

⭐ If you found this project helpful, consider giving it a star!
