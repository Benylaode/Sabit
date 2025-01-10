# Sabit
Adalah Aplikasih Absen otomatis yang memanfaatkan teknologi google form untuk mempermuda proses absensi dengan QR 
Berikut adalah README profesional untuk proyek **Sabit**:  

```markdown
# Sabit  

**Sabit** adalah aplikasi absensi otomatis yang dirancang untuk mempermudah proses absensi dengan memanfaatkan teknologi Google Form sebagai sistem eksternal dan integrasi QR Code untuk pengalaman pengguna yang cepat dan efisien.  

## Fitur Utama  
- **Absensi dengan QR Code**: Pengguna dapat melakukan absensi hanya dengan memindai QR Code yang telah disediakan.  
- **Integrasi Google Form**: Data absensi langsung tersimpan pada sistem Google Form untuk kemudahan akses dan pengelolaan.  
- **Tampilan Responsif**: Aplikasi dirancang agar nyaman digunakan di berbagai perangkat, baik smartphone maupun tablet.  
- **Notifikasi Real-Time**: Memberikan konfirmasi kepada pengguna setelah absensi berhasil dilakukan.  

## Teknologi yang Digunakan  
- **Frontend**: Dibangun menggunakan [Flutter](https://flutter.dev/) untuk pengembangan aplikasi lintas platform yang andal.  
- **Sistem Eksternal**: Memanfaatkan [Google Form](https://forms.google.com/) untuk pencatatan data absensi.  
- **QRCode Generation & Scanning**: Menggunakan pustaka Flutter untuk pembuatan dan pemindaian QR Code.  

## Instalasi dan Penggunaan  
Ikuti langkah-langkah berikut untuk menjalankan proyek ini di lokal Anda:  

### Prasyarat  
- Flutter SDK (versi terbaru direkomendasikan)  
- Akun Google untuk mengakses Google Form  
- Editor kode (seperti Visual Studio Code atau Android Studio)  

### Langkah-Langkah  
1. Clone repositori ini:  
   ```bash  
   git clone https://github.com/username/sabit.git  
   cd sabit  
   ```  

2. Install dependensi menggunakan Flutter:  
   ```bash  
   flutter pub get  
   ```  


3. Jalankan aplikasi:  
   ```bash  
   flutter run  
   ```  

4. Build aplikasi untuk distribusi:  
   - Android:  
     ```bash  
     flutter build apk  
     ```  
   - iOS:  
     ```bash  
     flutter build ios  
     ```  


## Kontribusi  
Kami menyambut kontribusi Anda untuk mengembangkan **Sabit** lebih baik lagi.  
1. Fork repositori ini.  
2. Buat branch fitur baru:  
   ```bash  
   git checkout -b fitur-anda  
   ```  
3. Commit perubahan Anda:  
   ```bash  
   git commit -m "Menambahkan fitur baru"  
   ```  
4. Push branch Anda:  
   ```bash  
   git push origin fitur-anda  
   ```  
5. Buat pull request.  

## Lisensi  
Proyek ini dilisensikan di bawah [MIT License](LICENSE).  

```  
