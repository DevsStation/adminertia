# Adminertia – Laravel + Inertia.js Admin Panel

> Modern, fast, developer-first admin panel built with Laravel 11, Inertia.js, and Tailwind CSS.
> Built in 5 days. Open source and production-ready. We will update this planning document time to time based on scopes.

![Banner](./assets/admInertia_banner_v-1.5.gif "Banner")

---

## ✨ Features

- 🔐 Auth (Fortify or Breeze)
- 🎛️ Modular Layout with Tailwind UI
- 🧑‍💼 Role & Permissions (spatie/laravel-permission)
- ⚙️ CRUD Generator (JSON → Inertia Views & Controller)
- 🌗 Dark Mode Toggle
- 📱 Fully Responsive Design
- 💬 Toasts, Modals, Loaders built-in

---

## 🛠 Tech Stack

| Backend    | Frontend               | UI           | Utilities        |
| ---------- | ---------------------- | ------------ | ---------------- |
| Laravel 11 | Vue 3 (via Inertia.js) | Tailwind CSS | Vite, Pint, Pest |

---

## 🚀 Quick Start

```bash
git clone https://github.com/devsstation/adminertia.git
cd adminertia

cp .env.example .env
composer install
php artisan key:generate
php artisan migrate --seed

npm install && npm run dev
php artisan serve
```

---

## 📦 Planned Premium Features

- Visual CRUD Builder (drag & drop)
- Team & Organization Support
- Multi-tenant SaaS Mode
- Audit Logs, Email Templates, File Manager
- Marketplace Modules

---

## 📸 Screenshots

Coming soon: CRUD demo, dashboard preview, dark mode toggle.

---

## 🧪 Testing

```bash
# Run backend tests
./vendor/bin/pest

# Frontend (coming soon)
npx playwright test
```

---

## 📣 Build In Public

This project was built in 5 days in public.
Follow the full journey: [#buildinpublic on X](https://x.com/search?q=adminertia%20%23buildinpublic)

---

## 🤝 Contributing

Pull requests, ideas, and bug reports welcome!
See [CONTRIBUTING.md](./CONTRIBUTING.md) and [issues](https://github.com/devsstation/adminertia/issues).

---

## 📄 License

[MIT](./LICENSE)

> 🔗 Development roadmap: see "[Adminertia Development Plan](https://twisty-stocking-85b.notion.site/Adminertia-Development-Plan-222a31c24b2e8078bc71e1f9661e05cb "Notion Doc: Adminertia Development Plan")" canvas or Notion doc

---

## Sponsores

Development Support: [DevsStation.com](https://DevsStation.com "Development support")

Hosting Support:  [BeingHosted.com](https://BeingHosted.com "Hosting/Server Support")
