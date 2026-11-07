# MEDISMART — berkas rilis

Repositori ini hanya berisi berkas rilis MEDISMART Desktop. Kode sumbernya disimpan di repositori privat.

Setiap rilis berisi:

- `MEDISMART-Setup-<versi>.exe`: installer Windows.
- `latest.json`: versi, tanggal, catatan perubahan, alamat unduhan, ukuran, dan hash SHA-256 installer.
  Aplikasi MEDISMART membaca berkas ini untuk memberi tahu pengguna bahwa versi baru tersedia.

Alamat tetap untuk versi terbaru:

```
https://github.com/tomyoktavian/medismart-rilis/releases/latest/download/latest.json
```

Rilis dibuat oleh skrip `scripts/release-public.sh` di repositori kode sumber. Jangan mengunggah berkas ke sini secara manual.
