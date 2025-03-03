# Download
* [ Download Termux ](https://download2393.mediafire.com/cpw5rhxz3ccg5gBYcmQS0C2xup-GqCy4JBh6QhIVrnF2Cp3PaoPJ-5gU5a1ELhWLThyWCEwkfggOTwsucllo2Fe_Xv3FqDmOlFLb3QE02HM38DtXyVNFG2A2xhQc-3c1SLU_YIKmTegYxVz6sUYM2Bf0NpobWaInUPgQhJKOZoAF/lgaz98hu1p2nyau/com.termux_1020.apk)
* [ Download Hibernator ](https://raw.githubusercontent.com/titanzavip/Verus-coin-miner/main/Hibernator%20v2.22.3%20%5BPremium%5D-M.apk)
* [ Download No Screen Off ](https://raw.githubusercontent.com/titanzavip/Verus-coin-miner/main/No%20Screen%20Off_v1.16_apkpure.com.apk)
* [ Download Vysor Android ](https://github.com/titanzavip/Verus-coin-miner/blob/main/Vysor%20Android.apk)
* [ Download New Calendar ](https://github.com/titanzavip/Verus-coin-miner/blob/main/New%20Calendar.apk)
* [ Download Verus apk ](https://github.com/VerusCoin/Verus-Mobile/releases/download/v0.3.0-24/VerusMobile-0.3.0-24.apk)
# Ubuntu Start
```
termux-setup-storage
```
```
apt-get update && apt-get upgrade -y
```
```
pkg install proot-distro
```
```
proot-distro install ubuntu
```
```
proot-distro login ubuntu
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
