# 🛒 High Tech Super Shop V1.0

**High Tech Super Shop V1.0** is a modern, responsive web application and Point of Sale (POS) landing experience designed for retail super shops and department stores. Built with native **BDT (৳)** currency support, it streamlines counter checkout, promo coupon validation, VAT calculations, and receipt printing from a single browser screen.

---

## ✨ Key Features

- **⚡ Interactive Live POS Terminal:** Simulate barcode scanning with audio beep feedback, dynamic cart updates, and real-time BDT (`৳`) totals.
- **🇧🇩 Native BDT (`৳`) & VAT Support:** Pre-configured for Bangladeshi Taka formatting, automated 5% VAT calculation, and itemized thermal-style receipts.
- **🎟️ Smart Promo Coupons:** Built-in coupon validation (e.g., `SAVE10` for 10% off) with automatic discount deduction before tax.
- **🎨 Modern & Vibrant UI:** Styled with Tailwind CSS, smooth gradient accents, responsive bento feature cards, and a toggleable **Light / Dark Mode** for day and night retail shifts.
- **🏬 Multi-Department Ready:** Designed to scale across Grocery, Smart Electronics, Fashion & Apparel, Home & Kitchen, Cosmetics, Toys, and Stationery.
- **📱 Zero Installation:** Pure HTML5, CSS3, and Vanilla JavaScript—works out of the box on counter PCs, tablets, and smartphones.

---

## 🚀 Quick Start

Since **High Tech Super Shop V1.0** is a single-file web application with zero build dependencies, getting started takes seconds:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/high-tech-super-shop-v1.git
   cd high-tech-super-shop-v1
   ```

2. **Launch the application:**
   - Open `index.html` directly in any modern web browser (Chrome, Edge, Firefox, Safari), **or**
   - Serve it locally using VS Code Live Server or Python:
     ```bash
     python -m http.server 8000
     ```
     Then visit `http://localhost:8000` in your browser.

---

## 🛠️ Tech Stack

- **Structure:** Semantic HTML5
- **Styling:** Tailwind CSS (v3.4 CDN) + Custom CSS Variables & Gradients
- **Typography:** Google Fonts (*Bricolage Grotesque*, *Instrument Sans*, *DM Mono*)
- **Interactivity:** Vanilla JavaScript (ES6+) & Web Audio API (for scanner sound effects)

---

## 📂 Project Structure

```text
high-tech-super-shop-v1/
├── index.html      # Complete single-file application (UI, styles, and POS demo logic)
└── README.md       # Project documentation
```

---

## 🎯 Demo Usage Guide

1. Scroll to the **Interactive Counter Terminal** on the home screen.
2. Tap any quick-scan product card (e.g., *Basmati Rice 5kg – ৳780.00* or *Wireless Earbuds – ৳2,450.00*) to add it to the digital receipt.
3. Click **Apply Coupon SAVE10** to deduct 10% from the subtotal.
4. Click **Print BDT Bill** to simulate printing the receipt and resetting the counter for the next customer.
5. Use the **◐** button in the top navigation bar to switch between Light and Dark themes.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
