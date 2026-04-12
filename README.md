# QuickBill POS 🚀

**QuickBill POS** is a premium, modern Point of Sale system specifically designed for small businesses in Sri Lanka. It features a sleek dark UI, high-end inventory management, and a unique **Facebook-style online shop** integrated with WhatsApp ordering.

## ✨ Premium Features

- 🔐 **Secure Login**: Professional admin login system with password toggles.
- 🖼️ **Facebook-Style Shop**: Automatically generates a public shop page with:
  - Cover Photos & Logos (Upload directly in POS)
  - Tabbed Interface (Products, Reviews, About)
  - Like/Favorite buttons & Search
  - Floating WhatsApp order button
- 🧾 **JPG Premium Invoices**: Professional invoices generated as high-quality images.
  - Custom Shop Branding
  - Customer Name & Contact details
  - Post-sale **Share to WhatsApp** / **Download JPG** bar
- 💱 **Global Currency Support**: Configurable currency symbols (Rs., $, LKR, etc.).
- 📦 **Inventory Manager**: CRUD support with image uploads and "Featured" product tagging.
- 📈 **Reports**: Daily sales, profit tracking, and low-stock indicators.

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Backend**: Node.js + Express.js
- **Database**: MongoDB (Mongoose Atlas)
- **Libraries**: Axios, html2canvas (JPG Invoices), FontAwesome 6

## 🚀 Quick Start

1. **Install Dependencies**:
   ```bash
   npm install
   ```
2. **Environment**: Create a `.env` file and add your `MONGO_URI`.
3. **Run Server**:
   ```bash
   node server.js
   ```
4. **Access**:
   - POS: `http://localhost:5000/login.html`
   - Shop: `http://localhost:5000/shop.html`

## 📖 Usage Highlights

- **Configure Shop**: Go to the **Shop Settings** (globe icon) to upload your logo/cover, set your Social links, and pick your theme color.
- **Billing**: Add Customer Name/Phone, select products, and click **Checkout** to see the new sharing menu.
- **Featured Items**: Check the "Featured" box in Product Management to highlight "HOT" items on your shop.

---
**Empowering Sri Lankan Entrepreneurs with Professional AI-Built Tools.**  
*Developed with excellence to help your business grow.*
