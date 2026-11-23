# ADv-Panel

**ADv-Panel** adalah kontrol panel manajemen server Linux berbasis *Single Binary Standalone Go Daemon* dengan antarmuka web modern yang tertanam langsung (*Embedded SPA*). Dirancang khusus untuk mengelola beban kerja **MC-ExamGO CBT**, **PHP-FPM**, **MySQL/MariaDB**, dan **Nginx**.

## Spesifikasi & Arsitektur
- **Core Engine:** Single Binary Standalone Go Daemon (Go 1.22+)
- **Internal Database:** Pure Go Zero-CGO SQLite (`modernc.org/sqlite` + WAL Mode)
- **Web UI Frontend:** Vue 3 + Vite + Tailwind CSS (`//go:embed`)
- **Linux Workload Target:** MC-ExamGO CBT, PHP-FPM, MySQL, Nginx

## Build dari Source
Pastikan **Go 1.22+** dan **Node.js 18+** sudah terinstal:

```bash
chmod +x build.sh
./build.sh
