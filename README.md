# 📚 Web Artikel dengan Sistem Login (CodeIgniter 4)

---

## 🚀 Fitur Utama

### 🔐 Authentication
- Login menggunakan email & password
- Password menggunakan hashing (`password_hash`)
- Session login (`logged_in`)
- Logout (destroy session)

### 🛡️ Authorization
- Halaman `/admin/*` dilindungi oleh **Auth Filter**
- User yang belum login akan diarahkan ke halaman login

### 📰 Manajemen Artikel
- Tambah artikel
- Edit artikel
- Hapus artikel
- List artikel

---

## 🗂️ Struktur Folder Penting

```text
app/
├── Controllers/
│   ├── User.php
│   └── Artikel.php
│
├── Models/
│   └── UserModel.php
│
├── Views/
│   ├── user/
│   │   └── login.php
│   │
│   └── artikel/
│       └── admin_index.php
│
├── Filters/
│   └── Auth.php
│
└── Config/
    ├── Routes.php
    └── Filters.php
```

---
