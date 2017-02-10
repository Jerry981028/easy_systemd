## Systemd serivce by SYHGroup  

 * [vncserver@.service](https://github.com/Jerry981028/easy_systemd/blob/master/vncserver%40.service)  
   ```
   wget https://github.com/Jerry981028/easy_systemd/raw/master/vncserver%40.service -O /etc/systemd/system/vncserver@.service  
   systemctl enable vncserver@1.service  
   vncserver :1  
   vncserver -kill :1  
   systemctl start vncserver@1.service  
   ```
   TIPS: `1` represents for port number.  

 * [x0vncserver@.service](https://github.com/Jerry981028/easy_systemd/blob/master/x0vncserver%40.service)  
   ```
   wget https://github.com/Jerry981028/easy_systemd/raw/master/x0vncserver%40.service -O /etc/systemd/system/x0vncserver@.service  
   systemctl enable x0vncserver@5901.service  
   systemctl start x0vncserver@5901.service  
   ```
   TIPS: `5901` represents for port number. For lightdm only.  

 * [shadowsocks-server.service](https://github.com/Jerry981028/easy_systemd/blob/master/shadowsocks-server.service)  
   ```
   wget https://github.com/Jerry981028/easy_systemd/raw/master/shadowsocks-server.service -O /etc/systemd/system/shadowsocks-server.service  
   systemctl enable shadowsocks-server.service  
   systemctl start shadowsocks-server.service  
   ```
   TIPS: For shadowsocks python version only.  

 * [chinadns.service](https://github.com/Jerry981028/easy_systemd/blob/master/chinadns.service)  
   ```
   wget https://github.com/Jerry981028/easy_systemd/raw/master/chinadns.service -O /etc/systemd/system/chinadns.service
   systemctl enable chinadns.service  
   systemctl chinadns.service  
   ```
   TIPS: For chinadns-c only.  

 * [shadowsocks-go.service](https://github.com/Jerry981028/easy_systemd/blob/master/shadowsocks-go.service)  
   ```
   wget https://github.com/Jerry981028/easy_systemd/raw/master/shadowsocks-go.service -O /etc/systemd/system/shadowsocks-go.service 
   systemctl enable shadowsocks-go.service 
   systemctl start shadowsocks-go.service 
   ```
   TIPS: For shadowsocks-go udp version only.  
