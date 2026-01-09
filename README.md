# 💸 MyDuitGua

<div align="center">

![Next.js](https://img.shields.io/badge/Next.js-16.1-black?style=for-the-badge&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=for-the-badge&logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-4.0-38B2AC?style=for-the-badge&logo=tailwind-css)
![Prisma](https://img.shields.io/badge/Prisma-6.2-2D3748?style=for-the-badge&logo=prisma)
![Supabase](https://img.shields.io/badge/Supabase-PostgreSQL-3ECF8E?style=for-the-badge&logo=supabase)

**Aplikasi Pelacak Keuangan Pribadi dengan Desain Modern "Liquid Glass"**

[Demo](#demo) • [Fitur](#fitur) • [Teknologi](#teknologi) • [Instalasi](#instalasi) • [Kontributor](#kontributor)

</div>

---

## 📖 Tentang

**MyDuitGua** adalah aplikasi manajemen keuangan pribadi yang dirancang untuk membantu pengguna melacak pemasukan, pengeluaran, anggaran, dan target keuangan mereka dengan mudah. Dibangun dengan antarmuka modern bergaya *Liquid Glass UI* yang memberikan pengalaman visual premium.

---

## ✨ Fitur

### 🏦 Manajemen Akun
- Tambah berbagai jenis akun (Bank, Tunai, E-Wallet)
- Pantau saldo tiap akun secara real-time
- Otomatis update saldo saat ada transaksi

### 💰 Pencatatan Transaksi
- Catat pemasukan dan pengeluaran
- Kategorisasi transaksi (Makanan, Transport, Gaji, dll)
- Pilih akun untuk setiap transaksi
- Riwayat transaksi dengan pencarian dan filter

### 📊 Dashboard & Statistik
- Ringkasan keuangan (Total Pemasukan, Pengeluaran, Saldo)
- Grafik interaktif (Harian, Mingguan, Bulanan, Tahunan)
- Visualisasi data menggunakan Recharts

### 📋 Anggaran (Budgets)
- Buat anggaran per kategori
- Pantau progress pengeluaran vs anggaran
- Notifikasi jika mendekati batas

### 🎯 Target Keuangan (Goals)
- Tetapkan target tabungan
- Pantau progress menuju target
- Deadline untuk setiap goal

### 👤 Profil Pengguna
- Personalisasi nama dan foto profil
- Ubah kata sandi
- Pengaturan akun

---

## 🛠️ Teknologi

| Kategori | Teknologi |
|----------|-----------|
| **Framework** | Next.js 16.1 (App Router) |
| **Bahasa** | TypeScript |
| **Styling** | Tailwind CSS 4.0 |
| **Database** | PostgreSQL (Supabase) |
| **ORM** | Prisma 6.2 |
| **Autentikasi** | NextAuth.js |
| **State Management** | Zustand |
| **Animasi** | Framer Motion |
| **Ikon** | Lucide React |
| **Charts** | Recharts |

---

## 🚀 Instalasi

### Prasyarat
- Node.js 18+ 
- npm atau yarn
- Akun Supabase (untuk database)

### Langkah-langkah

1. **Clone repository**
   ```bash
   git clone https://github.com/BryanAlexanderSantoso/MyDuitGua.git
   cd MyDuitGua
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Setup environment variables**
   
   Buat file `.env` di root folder:
   ```env
   DATABASE_URL="postgresql://YOUR_SUPABASE_URL"
   NEXTAUTH_SECRET="your-secret-key"
   NEXTAUTH_URL="http://localhost:3000"
   ```

4. **Sinkronisasi database**
   ```bash
   npx prisma db push
   npx prisma generate
   ```

5. **Jalankan development server**
   ```bash
   npm run dev
   ```

6. Buka [http://localhost:3000](http://localhost:3000) di browser.

---

## 📦 Deployment

Aplikasi ini dapat di-deploy dengan mudah ke **Vercel**:

1. Push kode ke GitHub
2. Hubungkan repository ke [Vercel](https://vercel.com)
3. Tambahkan environment variables
4. Deploy!

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/BryanAlexanderSantoso/MyDuitGua)

---

## 📱 Screenshots

<div align="center">
<i>Screenshots akan ditambahkan segera.</i>
</div>

---

## 🗂️ Struktur Folder

```
MyDuitGua/
├── prisma/
│   └── schema.prisma      # Database schema
├── public/                # Static assets
├── src/
│   ├── actions/           # Server Actions (CRUD)
│   ├── app/               # Next.js App Router pages
│   ├── components/        # React components
│   │   ├── dashboard/     # Dashboard components
│   │   └── ui/            # Reusable UI components
│   ├── lib/               # Utilities & configurations
│   └── store/             # Zustand state management
├── .env                   # Environment variables
└── package.json
```

---

## 👨‍💻 Kontributor

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/BryanAlexanderSantoso">
        <img src="https://github.com/BryanAlexanderSantoso.png" width="100px;" alt="Bryan Alexander Santoso"/>
        <br />
        <sub><b>Bryan Alexander Santoso</b></sub>
      </a>
    </td>
  </tr>
</table>

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

---

<div align="center">

**Made with ❤️ in Indonesia**

⭐ Jangan lupa kasih bintang kalau suka! ⭐

</div>
