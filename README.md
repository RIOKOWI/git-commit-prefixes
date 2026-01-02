# PREFIXES COMMIT MESSAGE FOR GIT

---

## INDO VERSION

### FIX = Perbaikan bug. Bukan nambah fitur.
```bash
    git commit -m "fix: mengatasi kesalahan pengguna null saat aplikasi dimulai"
```

### FEAT = Nambah fitur baru. Kalau cuma ubah kecil, jangan pakai ini.
```bash
    git commit -m  "feat: Tambahkan notifikasi push menggunakan Firebase Cloud Messaging."
```

### BUILD = Perubahan yang ngaruh ke build system atau dependency.
```bash
    git commit -m "build: Perbarui Gradle dan alat pembuatan Android."
```

### CHORE = Pekerjaan rutin, bersih-bersih, tidak ngaruh ke fitur atau behavior.
```bash
    git commit -m "chore: menghapus aset yang tidak digunakan dan membersihkan struktur proyek"
```

### CI = Perubahan pipeline CI/CD.
```bash
    git commit -m "ci: Tambahkan alur kerja GitHub Actions untuk pengujian Flutter."
```

### DOCS = Dokumentasi doang. Tidak nyentuh logic.
```bash
    git commit -m "docs: Perbarui README dengan petunjuk pengaturan Firebase."
```

### STYLE = Formatting, spasi, lint, tanpa ubah logic.
```bash
    git commit -m "style: Memformat file dan memperbaiki warning"
```

### REFACTOR = Restruktur kode, behavior tetap sama.
```bash
    git commit -m "refactor: Merestrukturisasi layanan otentikasi untuk pemisahan tanggung jawab yang lebih baik."
```

### PERF = Optimasi performa, memory, atau waktu eksekusi.
```bash
    git commit -m "perf: mengurangi pembaruan widget di layar beranda"
```

### TEST = Nambah atau perbaiki test.
```bash
    git commit -m "test: tambahkan unit test untuk layanan notifikasi"
```