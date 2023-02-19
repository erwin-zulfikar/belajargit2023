 *Buat username dan email terlebih dahulu
 git config --global user.name "erwinzulfikar"
 git config --global user.email "erwin_zulfikar@yahoo.com"

 *Cek apakah sudah masuk di konfigurasi
 git config --list

 *Inisialisasi git
 git init

 *Tambahkan konfigurasi untuk remote ke akun github, sebelumnya buat repo dulu di github
git remote add origin git@github.com:erwin-zulfikar/belajargit2023.git
git branch -M main
git add .
git commit -m "initial commit"
git push -u origin main