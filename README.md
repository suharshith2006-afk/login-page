# Portfolio Login Page — Task 2 (ApexPlanet Internship)

A responsive, single-file frontend login & signup portal built as part of the **Full Stack Web Development (PHP & MySQL)** internship at ApexPlanet Software Pvt. Ltd.

## 🌐 Project Overview

This is a fully client-side authentication UI with Sign In, Sign Up, and Guest access flows. It matches the exact color palette and design language of the main portfolio (`https://my-portfolio-3110.vercel.app/`). On successful login, the user is redirected to the live portfolio.

---

## ✅ Task 2 Requirements Covered

| Requirement | Status |
|---|---|
| Responsive Design (Mobile + Desktop) | ✅ |
| HTML5 Semantic Structure | ✅ |
| CSS3 Flexbox Layout | ✅ |
| CSS Animations & Transitions | ✅ |
| Media Queries | ✅ |
| JavaScript DOM Manipulation | ✅ |
| Form Validation (email format, required fields, password length) | ✅ |
| Event Handling (click, input, submit) | ✅ |

---

## 💡 Features

- **Sign In / Sign Up tabs** — smooth toggle between both forms
- **Password strength meter** — 6-rule live checker (length, uppercase, lowercase, number, symbol, 16+ bonus)
- **Confirm password match indicator** — real-time green/red feedback
- **Eye toggle** — show/hide password on all password fields
- **Guest access** — direct link to portfolio without logging in
- **Signup → Sign In flow** — after account creation, auto-switches to Sign In with email pre-filled
- **Success redirect overlay** — animated progress bar then redirects to portfolio
- **Floating particle background** — ambient canvas animation matching portfolio aesthetic
- **Fully responsive** — left branding panel hides on mobile, form stacks cleanly

---

## 🛠️ Tech Stack

- HTML5
- CSS3 (Flexbox, Custom Properties, Keyframe Animations, Media Queries)
- JavaScript ES6+ (DOM API, Event Handling, In-memory user store)

---

## 📂 File Structure

```
login-project/
│
└── login.html     # Complete self-contained file (HTML + CSS + JS)
```

---

## ⚙️ Local Setup (XAMPP)

1. Copy `login.html` into `C:\xampp\htdocs\portfolio\`
2. Start Apache from the XAMPP Control Panel
3. Open `http://localhost/portfolio/login.html`

> The `profile.jpeg` from your main portfolio folder is referenced for the signup avatar — make sure it's in the same directory.

---

## 🔮 Task 3 Upgrade Path

Currently the user store is in-memory JavaScript (resets on page refresh). In Task 3, replace `doSignIn()` and `doSignUp()` in the script with `fetch()` calls to PHP endpoints that read/write a MySQL `users` table:

```
users table: id | name | email | password_hash | created_at
```

---

## ⚖️ Legal

Developed as part of the ApexPlanet Software Pvt. Ltd. internship program — Task 2: Frontend Development with Responsive Design.

All rights reserved © 2026.
