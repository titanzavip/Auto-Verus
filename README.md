# Download
* [ Download Hibernator ](https://raw.githubusercontent.com/titanzavip/Verus-coin-miner/main/Hibernator%20v2.22.3%20%5BPremium%5D-M.apk)
* [ Download No Screen Off ](https://raw.githubusercontent.com/titanzavip/Verus-coin-miner/main/No%20Screen%20Off_v1.16_apkpure.com.apk)
* [ Download Vysor Android ](https://github.com/titanzavip/Verus-coin-miner/blob/main/Vysor%20Android.apk)
* [ Download New Calendar ](https://github.com/titanzavip/Verus-coin-miner/blob/main/New%20Calendar.apk)
# OS-INSTALLER
```
termux-setup-storage
```
```
apt update -y
```
```
apt upgrade -y
```
```
apt install git -y
```
```
pkg install nano
```
```
cd /data/data/com.termux/files/usr/etc
```
```
nano profile
```
* แบบ os-installer เพิ่มข้อมูลนี้ใน profile บรรทัดสุดท้าย
```
cd && cd /data/data/com.termux/files/usr/etc/os-install
sh ubun.sh
```
```
cd
```
```
git clone https://github.com/mantvmass/os-installer
```
```
cd os-installer
```
```
sh build.sh
```
Open Os
```
os-installer
```
# AUTO RUN CCMINER IN TERMUX
```
os-installer
```
```
apt update -y
```
```
apt upgrade -y
```
```
apt-get install git -y
```
```
git clone https://github.com/titanzavip/Auto-Verus
```
```
cd Auto-Verus
```
```
sh setup.sh
```
* หลังจากเปิดไฟล์ bash.bashrc เพิ่มบรรทัดแรกเป็น
```
run-miner
```
* แล้ว save

## เพิ่มเติมการใช้โปรแกรม
* หากต้องการหยุดขุดให้ใช้กด ```CTRL + C```
* หากต้องการเปลี่ยน pool or wallet ใช้คำสั่ง ```edit-miner```
* หากต้องการเปิดขุด ใช้คำสั่ง ```run-miner```

# ZergPool
 * Doge
```
stratum+tcp://verushash.asia.mine.zergpool.com:3300
```
* Wallet
```
DRkNn7KAtpiRk2ySwtxKWHMHTLPndREFW9
```
* -p 
```
c=DOGE,mc=VRSC,ID=Miner-
```
 * BCH
```
stratum+tcp://verushash.asia.mine.zergpool.com:3300
```
* Wallet
```
0x7066099a5da8f1019824634e7f5c59d050de0f99
```
* -p 
```
c=BCH,mc=VRSC,ID=Realme-
```
# Luckypool
```
stratum+tcp://ap.luckpool.net:3956 
```
```
RJmusWhHL5qvDa1iK3CF7NWYaSHG5P9gyQ.Realme-
```
```
x
```
```
edit-miner
```
```
run-miner
```
