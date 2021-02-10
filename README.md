# HomeAutomation

von https://ei23.de/diy-smarthome/



1. Raspberry Pi   
1.1 Raspberry PI Imager   
1.2 Raspberry Pi OS Lite  
1.3 Enable SSH mit ssh.txt  
1.4 IP Adress fix: 192.168.150.24  
1.5 user - pw   


2. Local PC
2.1 Putty

3. ei23 von  ei23.de  
3.1 Zeile 1 (damit wird das Skript geladen)  
      wget -q "https://ei23.de/softwarehub/smarthome/f7a1d1e13827f0d6b95c53ee54eaccd1/ei23.sh" -O ei23.sh  
    Zeile 2 (damit wird das Skript ausgeführt)  
      bash ei23.sh  
      
      installiert https://github.com/PeterS07/HomeAutomation/blob/main/ei23infos
            
      
3.2 User
   | User |  nutzung | spalte3 | port |
   |------|----------| ------- | ---- |
   | pi | user für pi |  |
   | homered | user  für nodered | flipperred|
   | homemqtt| mqtt | flippermqtt |
   | admin | portainer | dockerflipper | 9000 |
   | admin | grafana | flippergrafana |3000 |
