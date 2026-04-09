# 🛒 ScriptAdda – Digital Script Marketplace

A modern **Digital Marketplace Platform** (like Codecanyon) built using **Qwik, Vite, Tailwind CSS, PostgreSQL & MinIO**, where users can browse, upload, and sell digital scripts, templates, and assets.

---

## 🚀 Features

* 🛍️ Digital Product Marketplace (Scripts, Templates, Assets)
* 👤 User Authentication System
* 📦 Product Upload & Management
* 💳 Purchase / Download System (Planned / Extendable)
* ☁️ File Storage using MinIO (S3 Compatible)
* 🗄️ PostgreSQL Database Integration
* ⚡ Ultra Fast UI with Qwik Framework
* 🎨 Modern UI with Tailwind CSS
* 🔍 Search & Filtering System
* 📱 Fully Responsive Design

---

## 🛠️ Tech Stack

* **Frontend:** Qwik + Qwik City
* **Styling:** Tailwind CSS
* **Backend:** Node.js (Qwik SSR)
* **Database:** PostgreSQL :contentReference[oaicite:0]{index=0}  
* **Storage:** MinIO (Object Storage) :contentReference[oaicite:1]{index=1}  
* **Build Tool:** Vite :contentReference[oaicite:2]{index=2}  
* **Language:** TypeScript :contentReference[oaicite:3]{index=3}  

---

## 📂 Project Structure

```
project/
│
├── src/
│ ├── routes/ # Pages (Routing system)
│ ├── components/ # Reusable components
│
├── public/ # Static assets
│
├── docker-compose.yml # Database & Storage setup
├── package.json # Scripts & dependencies
├── vite.config.ts # Build configuration
├── tsconfig.json # TypeScript config
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/scriptadda.git
cd scriptadda
```


2️⃣ Install Dependencies
```bash
npm install
```


3️⃣ Start Development Server
```bash
npm run dev
```

4️⃣ Run Docker Services (IMPORTANT)
```bash
👉 Database & Storage start karo:

docker-compose up -d

👉 Services include:

PostgreSQL → localhost:5432
MinIO → http://localhost:9001
```

5️⃣ Build Project
```bash
npm run build
```

6️⃣ Preview Production
```bash
npm run preview
🐳 Docker Configuration
```


npm run lint      # Run ESLint
npm run fmt       # Format code
