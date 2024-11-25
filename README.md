[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/tbEHDGEc)
# Git and Github Introduction

| Nama  | Division        | Sub-Division  |
| ----- | ---------- | ---------- |
| M. Faqih Ridho   | PGR | Vision |

![alt text](https://github.com/Magang-Barunastra-2024/git-and-github-introduction-MFaqihRidh0/blob/main/Prototipe%20kapal%20Barunastra%20Github%20tugas.jpeg?raw=true)
**## Early Procedure 
##Install Git:
Unduh dan instal Git dari git-scm.com.
Periksa instalasi dengan menjalankan perintah berikut di terminal:
bash
Salin kode
git --version
Konfigurasi Git:
Atur nama pengguna dan email Anda:
bash
Salin kode
git config --global user.name "Nama Anda"
git config --global user.email "email@anda.com"
Buat Akun GitHub:
Daftarkan akun di GitHub.
Create Repository
Cara Membuat Repository di GitHub:

Login ke akun GitHub Anda.
Klik ikon + di kanan atas halaman GitHub, lalu pilih "New Repository".
Isi nama repository Anda.
Tambahkan deskripsi (opsional).
Pilih pengaturan visibilitas (Public/Private).
Klik tombol "Create Repository".
Clone Repository ke Lokal (Opsional):

Salin URL repository yang telah dibuat.
Buka terminal dan jalankan:
bash
Salin kode
git clone <URL-repository>
Ini akan menyalin repository ke komputer Anda.
Push File from Local to GitHub
Cara Push File dari Lokal ke GitHub:

Tambahkan file ke direktori repository lokal.
Inisialisasi repository lokal (jika belum dilakukan):
bash
Salin kode
git init
Tambahkan file ke staging area:
bash
Salin kode
git add .
Commit perubahan:
bash
Salin kode
git commit -m "Pesan commit"
Hubungkan repository lokal ke GitHub:
bash
Salin kode
git remote add origin <URL-repository>
Push file ke GitHub:
bash
Salin kode
git push -u origin main
##Create New Branch in GitHub
Cara Membuat Branch Baru:

Buat branch baru di lokal:
bash
Salin kode
git branch <nama-branch>
Pindah ke branch tersebut:
bash
Salin kode
git checkout <nama-branch>
Push branch baru ke GitHub:
bash
Salin kode
git push -u origin <nama-branch>
##Delete Branch in GitHub
Cara Menghapus Branch di GitHub:

Pastikan branch yang akan dihapus tidak sedang aktif.
Hapus branch di lokal:
bash
Salin kode
git branch -d <nama-branch>
Hapus branch di GitHub:
bash
Salin kode
git push origin --delete <nama-branch>
##Merging Branch in GitHub
Cara Melakukan Merging Branch:

Pindah ke branch utama (misalnya main):
bash
Salin kode
git checkout main
Merge branch lain ke branch utama:
bash
Salin kode
git merge <nama-branch>
Push perubahan ke GitHub:
bash
Salin kode
git push origin main
##Other Procedure
Melihat Log Commit:
bash
Salin kode
git log
Melihat Daftar Branch:
bash
Salin kode
git branch
Membatalkan Perubahan:
Hapus perubahan pada file tertentu:
bash
Salin kode
git checkout -- <nama-file>
Reset ke commit sebelumnya:
bash
Salin kode
git reset --hard <commit-id>
