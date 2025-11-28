# FreshWash - Laundry Service Management System

FreshWash adalah aplikasi web untuk manajemen layanan laundry yang memudahkan pelanggan untuk melakukan reservasi dan admin untuk mengelola pesanan.

## 🚀 Fitur

- 🔐 Autentikasi (Login/Register)
- 👤 Manajemen Profil Pengguna
- 📅 Sistem Reservasi Laundry
- 📊 Dashboard Admin
- 📱 Responsive Design
- 🔍 Riwayat Pesanan
- ⭐ Sistem Review

## 🛠 Tech Stack

### Frontend
- React + Vite
- React Router DOM
- Axios
- CSS3

### Backend
- Node.js + Express
- MySQL
- JWT Authentication
- Multer (Upload Files)

## 📦 Installation

### Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/freshwash.git
cd freshwash
```

## 🖥 Frontend Setup

```bash
cd freshwash-frontend
npm install
```

Copy `.env.example` to `.env` dan sesuaikan konfigurasi:

```bash
cp .env.example .env
```

Jalankan development server:

```bash
npm run dev
```

Frontend akan berjalan di `http://localhost:5173`

## 🛢 Backend Setup

```bash
cd freshwash-backend
npm install
```

Copy `.env.example` to `.env` dan sesuaikan konfigurasi database:

```bash
cp .env.example .env
```

Edit file `.env` dengan kredensial database Anda:

```
PORT=3000
DB_HOST=localhost
DB_USER=root
DB_PASS=your_password
DB_NAME=freshwash_db
JWT_SECRET=your_jwt_secret_key
```

Import database schema (jika ada file SQL)

Jalankan development server:

```bash
npm run dev
```

Backend akan berjalan di `http://localhost:3000`

## 📁 Project Structure

```
freshwash/
├── freshwash-frontend/          # React Frontend
│   ├── src/
│   │   ├── components/         # Reusable components
│   │   ├── pages/              # Page components
│   │   ├── context/            # React Context
│   │   ├── layouts/            # Layout components
│   │   └── routes/             # Route configuration
│   └── public/                 # Static files
│
└── freshwash-backend/          # Express Backend
    ├── config/                 # Configuration files
    ├── controllers/            # Route controllers
    ├── middlewares/            # Custom middlewares
    ├── models/                 # Database models
    ├── routes/                 # API routes
    └── uploads/                # Upload directory
```

## 🔑 Environment Variables

### Frontend (.env)
```
VITE_API_URL=http://localhost:3000/api
VITE_ENV=development
```

### Backend (.env)
```
PORT=3000
DB_HOST=localhost
DB_USER=root
DB_PASS=
DB_NAME=freshwash_db
JWT_SECRET=your_jwt_secret
```

## 👥 User Roles

- **Customer**: Dapat membuat reservasi, melihat riwayat, dan memberikan review
- **Admin**: Dapat mengelola semua reservasi, user, dan review

## 📝 License

MIT License

## 👨‍💻 Author

Your Name

---

⭐ Jika project ini membantu, berikan star di repository ini!
