# Tugas Akhir 2 - Praktikum Jaringan Komputer

## Link Youtube Penjelasan
https://youtu.be/6-CEyNdiT3w

## Hasil Capture Saat Gagal Melakukan Ping
<img width="873" height="385" alt="Screenshot 2025-11-04 225229" src="https://github.com/user-attachments/assets/11a37abb-30f0-422e-9cb4-0cc61f681277" />

> Saat awal percobaan, router belum dikonfigurasi, yang artinya interface router yang menjadi default gateway bagi masing-masing LAN belum diberi IP address dan belum diaktifkan. Akibatnya, tidak ada perangkat Layer 3 yang bisa meneruskan paket ICMP dari satu jaringan ke jaringan lainnya, sehingga proses ping gagal.

## Hasil Capture Saat Berhasil Melakukan Ping
<img width="872" height="436" alt="Screenshot 2025-11-04 230710" src="https://github.com/user-attachments/assets/040b67f7-929b-440d-9567-dbbf435dac13" />

> Setelah konfigurasi dilakukan, maka IP address pada interface router disetting dan interface diaktifkan (no shutdown), sehingga router dapat mulai melakukan fungsi routing. Paket ICMP dari PC pada subnet pertama dapat dikirim ke subnet lain melalui router.
