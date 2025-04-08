#### ZTE-C300 Configuration
Script untuk menampilkan SN Modem di salah satu port
#show gpon onu baseinfo gpon-olt_1/5/1
Menampilkan redaman pada port 
#show inter optical-module-info gpon-olt_1/3/5

Menambahkan Card GTGO / GTGH di C300/C320
Register GTGH
#conf t
#add-card rackno 1 shelfno 1 slotno 2 GTGH
#end
#wr

Status INSERVICE
#conf t
#int gpon-olt_1/2/1-16
#no sh
#end
#wr

