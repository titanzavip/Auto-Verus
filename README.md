# AUTO RUN CCMINER IN TERMUX

Setting Step
```
apt-get update
```
```
apt-get install git -y
```
```
git clone https://github.com/mantvmass/auto-run-ccminer
```
```
cd auto-run-ccminer
```
```
sh setup.sh
```
* หลังจากเปิดไฟล์ bash.bashrc เพิ่มบรรทัดแรกเป็น
- ```run-miner```
* แล้ว save

## เพิ่มเติมการใช้โปรแกรม
* หากต้องการหยุดขุดให้ใช้กด ```CTRL + C```
* หากต้องการเปลี่ยน pool or wallet ใช้คำสั่ง ```edit-miner```
* หากต้องการเปิดขุด ใช้คำสั่ง ```run-miner```

 
