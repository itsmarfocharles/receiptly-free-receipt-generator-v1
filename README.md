# 🧾 Receiptly — Free Receipt Generator

**Create professional receipts for free — no account, no subscription, and no watermark.**

Receiptly is a modern, lightweight, open-source receipt generator built for individuals, freelancers, shops, small businesses, and anyone who needs to create a professional receipt quickly.

It runs directly in the browser and does not require a database, backend, or user account.

---

## ✨ Features

* 🧾 Professional receipt generation
* 🏢 Business information
* 🖼️ Business logo upload
* 👤 Customer information
* 📦 Add multiple products or services
* 🔢 Automatic quantity and price calculations
* 💰 Automatic subtotal and total
* 🏷️ Discounts
* 📊 Tax calculation
* 💳 Multiple payment methods
* 🌍 Multiple currencies
* 🇬🇭 Ghana Cedi (₵) support
* 📱 Mobile-friendly design
* 🖨️ Print receipts
* 📄 Download receipts as PDF
* 🔲 QR code generated for every receipt
* 📲 Progressive Web App (PWA)
* 📥 Browser installation prompt when supported
* 🌐 Works on desktop, tablet and mobile
* 🔐 No account required
* 🗄️ No database required
* 💸 Completely free
* 🚫 No watermark

---


## 💻 Run Locally

Receiptly is a static website, so you don't need Node.js, PHP, Python frameworks, databases, or a server.


Download the repository and extract it.

Then run it using a local web server.


## ☁️ Deploy to GitHub Pages

You can host Receiptly completely free using GitHub Pages.

### 1. Create a repository

Create a new GitHub repository called:

```text
receiptly
```

### 2. Upload the project

Upload all project files to the repository.

### 3. Enable GitHub Pages

Go to:

**Settings → Pages**

Choose:

```text
Deploy from a branch
```

Select:

```text
main
/
```

Then save.

GitHub will provide your live website.

---

## ☁️ Deploy to Cloudflare Pages

Receiptly works with Cloudflare Pages because it is a static website.

Connect your GitHub repository to Cloudflare Pages.

### Build settings

```text
Framework preset: None
Build command: None
Build output directory: /
```

After deployment, Cloudflare will provide a free `pages.dev` address.

You can also connect your own domain.

---

## 🎨 Rebrand Receiptly

Receiptly is designed to be easy to customize.

You can change:

* Brand name
* Logo
* Colors
* Fonts
* Text
* Receipt design
* Currency options
* Footer
* Website description
* PWA name
* App icon

For example, change:

```text
Receiptly
```

to:

```text
YourBrand
```

You can also replace the logo in:

```text
/icons/
```

and customize the colors in:

```text
/styles.css
```

---

## 📱 PWA Installation

Receiptly is a Progressive Web App.

When the browser supports the installation prompt, the website displays an:

**Install App**

button.

The button uses the browser's native PWA installation system.

After installation, Receiptly can behave like an app on supported devices.

---

## 🔲 QR Codes

Every receipt receives a QR code containing the receipt information.

The QR code can contain information such as:

```text
Receipt number
Business name
Customer
Date
Currency
Items
Total
```

The current version uses a **self-contained QR payload**, meaning a database is not required.

This helps keep Receiptly:

* Free
* Lightweight
* Private
* Easy to deploy
* Easy to rebrand

---

## 🔒 Privacy

Receiptly does not require an account.

There is no Receiptly database storing your receipts.

Receipt information is processed in the browser.

Your business information, customer information and receipt data are not required to be uploaded to a Receiptly server.

---

## 🧩 Technology

Receiptly is built with standard web technologies:

```text
HTML
CSS
JavaScript
PWA
Service Worker
QR Code
PDF generation
```

There is no required:

* Supabase
* Firebase
* PHP
* Node.js backend
* Database
* Authentication system

---

## 🛠️ Project Structure

```text
receiptly/
│
├── index.html
├── styles.css
├── app.js
├── manifest.webmanifest
├── sw.js
├── README.md
├── LICENSE
│
└── icons/
    └── icon.svg
```

---

## 🤝 Free to Reuse

Receiptly is open source.

You are allowed to:

* Download it
* Copy it
* Modify it
* Rebrand it
* Add features
* Host it yourself
* Use it for personal projects
* Use it for business projects
* Use it commercially
* Create your own version

You do **not** need to ask for permission.

Please see the `LICENSE` file for the complete terms.

---

## ⭐ Support the Project

If you find Receiptly useful:

⭐ Star the repository

🍴 Fork the project

🐛 Report bugs

💡 Suggest improvements

🔧 Submit improvements through pull requests

---

## 📄 License

Receiptly is released under the **MIT License**.

---

## 👨‍💻 Built By

**Charles Marfo**

Receiptly is an open-source project created to make professional receipt generation accessible to everyone.

---

### Make receipts. Keep it simple. Keep it free.

**Receiptly — Professional receipts without the cost.**
