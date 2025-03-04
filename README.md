# Download
* [ Download Termux ](https://download2263.mediafire.com/7etr61e7abygBR7BvgJDU6sobhsJ2TR7WsxitiuuCUY5l3WP86GnoKwMKXZQUzIAl2H55uWHVYUFed1QPdmJemZ4dO7z6iu73_p-TbzvcxKazda9GkkW23S6nagz9qiy7MIwQqFKK6c821ueiupKk5EHLRJE1bdTK5kyC9JOKN-R/ffgnbvqh7cbdhex/termux-app_v0.118.0%2Bgithub-debug_arm64-v8a.apk)
* [ Download Hibernator ](https://raw.githubusercontent.com/titanzavip/Verus-coin-miner/main/Hibernator%20v2.22.3%20%5BPremium%5D-M.apk)
* [ Download No Screen Off ](https://raw.githubusercontent.com/titanzavip/Verus-coin-miner/main/No%20Screen%20Off_v1.16_apkpure.com.apk)
* [ Download Vysor Android ](https://github.com/titanzavip/Verus-coin-miner/blob/main/Vysor%20Android.apk)
* [ Download New Calendar ](https://github.com/titanzavip/Verus-coin-miner/blob/main/New%20Calendar.apk)
* [ Download Verus apk ](https://github.com/VerusCoin/Verus-Mobile/releases/download/v0.3.0-24/VerusMobile-0.3.0-24.apk)
* [ Download Termux Backup ](https://download851.mediafire.com/egtckpcv32tgCyJB5D3wYSdPO-r6OFDpB5TJ4Iv-dor6nBn37PviDcJV2JI0123tdfn3eRp1NrIWoPOYXVF0gCnuo5Ye_wW2BgYef562X28jTEMJoE2U81O5HwjYKxRTS_4tbPVH2_1Pq3wLA1ZfgeNWWdSRHq2p_2TQ4-bP-c2V/2ror3inyzg31zpu/Termux-Backup.tar.gz)

# Termux Backup
```
termux-setup-storage
```
```
cd /data/data/com.termux/files && tar -zvxf /storage/emulated/0/download/Termux-Backup.tar.gz --recursive-unlink --preserve-permissions && proot-distro login ubuntu
```

# Termux 
https://github.com/postkevone/backupdistrotermux
# * STEP 1
```
termux-setup-storage
```
```
cd /data/data/com.termux/files/usr/etc
```
```
nano profile
```
เพิ่มข้อมูลนี้ใน profile บรรทัดสุดท้าย
```
cd && cd /data/data/com.termux/files/usr/etc/os-install
sh ubun.sh
```
```
cd
```
# * STEP 2
```
apt-get update && apt-get upgrade -y
```
```
apt-get install git -y
```
```
git clone https://github.com/titanzavip/os-installer.git
```
```
cd os-installer
```
```
chmod +x os-installer
```
```
sh build.sh
```
# AUTO RUN CCMINER IN TERMUX
```
apt-get update && apt-get upgrade -y
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
* Verus Coin
```
stratum+tcp://verushash.asia.mine.zergpool.com:3300
```
* Wallet
```
RJmusWhHL5qvDa1iK3CF7NWYaSHG5P9gyQ.Realme-
```
* -p 
```
c=VRSC,mc=VRSC
```
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
verus
```
```
equi
```
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

Safe Trade
```
RQAfPvMpdiwNsiRXfMk5N2PBJ9aXaZQArv
```
