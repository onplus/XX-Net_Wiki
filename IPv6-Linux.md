安装虚拟网卡miredo
   ## sudo apt install miredo
查看网卡配置ifconfig
   ## 在结果中应该能看见一个叫 teredo 的虚拟网卡
但是重启系统之后，需要重启开启miredo
   ## sudo miredo    
  
来源于这个帖子http://www.linuxidc.com/Linux/2013-03/80479.htm
其他linux系统也应该能安装这个包，操作差不多。自己查询一下就好了