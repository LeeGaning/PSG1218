叉自 keke1023，感谢 keke、vb1980、sunnyguhz 等大神的工作。  
以下附上 keke 和其他五位大神的源码地址供参考：
https://github.com/vb1980/Padavan-KVR  
https://github.com/keke1023/Padavan  
https://github.com/hanwckf/rt-n56u  
https://github.com/chongshengB/rt-n56u  
https://github.com/padavanonly/rt-n56u  
https://github.com/immortalwrt/padavan

固件默认 wifi 名称 sunnygu 及 sunnygu_5G  
wifi 密码 1234567890  
默认管理地址 192.168.8.1  
默认管理账号密码都是 admin

特点：
MTK 全家桶破解支持 KVR  
已测试机型：  
PSG1208：KR  
PSG1218：KR  
ZTE_E8820S：2.4G：KVR，5G：KR  
BELL-A-040W-Q：KVR

KVR 组网需要把所有路由器都刷上支持 KVR（至少要支持 K）的固件，并把 wifi 名称和密码设成一样。信道建议岔开，一般会自动岔开不用管，也可以手动指定。除了作为主路由的路由器以外，其他路由器设置成 AP 模式。
最后，你的手机需要支持 KVR 漫游。目前我手上的手机漫游效果：苹果=红米 Note8pro>RealmeGTneo，华为/荣耀可能不能漫游或者漫游效果较差（不确定，他们之前自己官方这么说的）

看信道用 wifianalyzer，测试漫游效果用 wifi 测评大师，查看 KVR 支持情况用 win10 电脑上的 winfi
