# ifconfig
```
1.IP位置







```

```
2.遮罩Mask








```
```
3.Gateway




```
```
有三個介面(interfaces):
[1]docker 0
[2]eth0 實體網卡
[3]lo==loaclhost每一台電曩都會有本地端位址  127.0.0.1
```
```
解釋下列資訊的意義:
mtu 1500
inet 172.17.0.1  
netmask 255.255.0.0  
broadcast 172.17.255.255
ether 02:42:a0:1e:82:96
```







``` 
問題1.IP位置
問題2.mtu 1500  最大傳輸單元Maximum Transmission Unit  https://en.wikipedia.org/wiki/Maximum_transmission_unit
問題3.MAC address==實體網卡位址==>ether 08:00:27:2a:d5:62
問題4.broadcast address==https://en.wikipedia.org/wiki/Broadcast_address
問題5.lo==localhost address=?





```
# ping 172.17.0.1
