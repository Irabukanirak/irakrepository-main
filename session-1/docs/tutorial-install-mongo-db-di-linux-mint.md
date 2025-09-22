# Tutorial Menginstal MongoDB di Linux Mint
## Step 1: Buka Situs MongoDB
Buka situs [MongoDB](www.mongodb.com) di Firefox. 
## Step 2: Navigasi ke Dokumentasi Server MongoDB
Kemudian klik "Resources", pilih "Server Documentation", lanjutkan ke "MongoDB Community", dan klik "Install on Linux". 
## Step 3: Import Public Key dan Public GPG Key pada Terminal Linux Mint
Karena menggunakan Linux Mint, pilih opsi "Install on Ubuntu" karena paling mendekati. Copy import the public key gnupg dan curl; `sudo apt-get install gnupg curl` dan `curl -fsSL https://www.mongodb.org/static/pgp/server-8.0.asc |    sudo gpg -o /usr/share/keyrings/mongodb-server-8.0.gpg    --dearmor`, lalu paste di terminal dan tekan Enter. 
## Step 4: Mengupdate Repository dan Menginstall MongoDB
Setelah itu, copy `sudo apt-get update`, paste di dalam terminal, dan tekan Enter. Lakukan hal yang sama dengan `sudo apt-get install -y mongodb-org`, lalu tekan Enter. Dengan begitu, proses pengunduhan MongoDB selesai.
