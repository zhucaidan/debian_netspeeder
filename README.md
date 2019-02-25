# debian_netspeeder

1、Net-speeder Debian/Ubuntu 一键包

2、Requirements
   Debian7 32 & 64 bit
   Debian8 32 & 64 bit 
   Debian9 32 & 64 bit

3、Install
   wget --no-check-certificate https://raw.githubusercontent.com/zhucaidan/debian_netspeeder/master/debian_netspeeder.sh

   chmod a+x debian_netspeeder.sh

   bash debian_netspeeder.sh

4、Commend
   查看 net-speeder 是否运行
   ps aux|grep net_speeder|grep -v grep

   停止net-speeder
   killall net_speeder

   启动net-speeder（OPENVZ环境）
   nohup /root/net_speeder venet0 "ip" >/dev/null 2>&1 &
   
5、Double
   再次运行即可开启四倍发包
   nohup /root/net_speeder venet0 "ip" >/dev/null 2>&1 &
