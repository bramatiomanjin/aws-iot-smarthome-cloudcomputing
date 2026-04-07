# 🏠 IoT Smart Home Monitoring System - AWS
Proyek UAS Cloud Computing - Teknik Informatika UPR 2026.

## 👥 Anggota Kelompok & Peran
| Nama Anggota | NIM | Peran | Tanggung Jawab |
| :--- | :--- | :--- | :--- |
| **Bramatio Manjin** | 2330205030052 | DevOps Engineer | Pengelolaan Git, persiapan infrastruktur (Terraform/IaC). |
| **Ciko Christian** | 2330205030059 | Cloud Architect | Desain arsitektur, pemilihan layanan, dan optimasi biaya. |
| **Gregio Rafael Leon Jordan** | 2330305030072 | Backend Developer | Implementasi kode Lambda, integrasi SNS, dan kebijakan IAM. |
| **Haryadi Yusuf** | 2330305030074 | Security Engineer | Konfigurasi enkripsi data, audit keamanan, dan manajemen sertifikat. |

## 📊 Arsitektur Sistem (Final Minggu 1)
![Architecture Diagram](docs/DiagramArsitektur.png)

## 📄 Dokumen Proyek
- [📖 Laporan Perencanaan Proyek (PDF)](docs/Dokumen_Perencanaan_Proyek.pdf)
- [💰 Estimasi Biaya AWS - $3.82/Bulan (PDF)](docs/Estimasi_Biaya_AWS.pdf)

## 🛠️ Detail Layanan (AWS Singapore Region)
- **AWS IoT Core**: Gateway MQTT untuk sensor (43.200 pesan/bulan).
- **AWS Lambda**: Pemrosesan logika dan deteksi anomali (43.200 request/bulan).
- **Amazon CloudWatch**: Monitoring dashboard untuk 5 metrik sensor (Suhu, Kelembapan, Gerak, Gas, Lampu).
- **Amazon DynamoDB & S3**: Penyimpanan data real-time dan arsip log (Standard Storage 1 GB).
- **Amazon SNS**: Pengiriman notifikasi peringatan (Email/SMS).