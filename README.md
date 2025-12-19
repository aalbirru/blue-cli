# MYnyak Engsel Sunset X blue-cli

![banner](bnr.png)

CLI client for a certain Indonesian mobile internet service provider.

# cara menggunakan dengan TMK

catatan untuk yang baru pertama kali pakai termux install ini dulu

copy paste semua di termux lalu enter, lakukan saat satu 

### pilih salah satu metode mau A atau B , jika ingin install saja gunakan metode A

## metode A
#### install tanpa melihat semua log paket yang di install 
1. update 
```
pkg update && pkg upgrade -y
```
2. Install Git
```
pkg install git -y
```
3. Clone this repo
```
git clone https://github.com/aalbirru/blue-cli
```
4. Open the folder
```
cd blue-cli
```
5. Setup
```
bash setup.sh
```
Menambahkan Environment Variables:
1. Buka https://rentry.co/blue-cli & copy
2. Bikin file .env di dalam folder blue-cli dengan isi text yang sudah di-copy tadi di dengan cara ketik
```
nano .env
```
enter
paste
ctrl+x
y
enter

6. Run the script
```
python main.py
```
## metode B
#### jika kamu ingin melihat log paket yang diinstal gunakan metode ini 
```
apt update && apt full-upgrade
```
```
pkg install git
```
```
pkg install python
```
```
apt install python-pillow

```
```

git clone https://github.com/aalbirru/blue-cli
```
```
cd blue-cli
```
```
pip install -r requirements.txt
```

Menambahkan Environment Variables:
1. Buka https://rentry.co/blue-cli & copy
2. Bikin file .env di dalam folder blue-cli dengan isi text yang sudah di-copy tadi di dengan cara ketik
```
nano .env
```
enter
paste
ctrl+x
y
enter

6. Run the script
```
python main.py
```
