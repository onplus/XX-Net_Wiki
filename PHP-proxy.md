##概述
由于GoAgent对某些网站有限制，比如：
+ Youtube的某些视频，对某些地区是有限制的
+ 类似Pinterest等网站，限制GAE（GoAgent）的访问

另外一个担忧，Google ip有可能某一天会被封锁完，因此，需要寻找备用方法。  

##PHP 代理
### 原理：
世界上有很多的免费PHP空间，而且这些服务商托管着大量的商业网站，封锁的影响太大，虽然慢一些，但是仍然是一种翻墙的方法。

### 如何寻找
Google 寻找 “免费PHP空间” ，或者 "Free PHP host"

### 如何部署
+ 申请空间
+ 上传部署服务端程序  
  把php_proxy/x.x.x/server目录下的文件，上传到服务端  
  不同服务商的上传方式不同，有些是ftp，有的是git，有支持http的，需要查看对于的部署手册
+ 测试  
  上传完之后，先测试链接地址是否有效，可以在浏览器中直接输入，看是否有提示正确的内容  
+ 配置  
  在PHP模块的配置页面中配置
+ 使用  
  浏览器中，使用SwitchSharp中，导入配置文件  
  选择PHP或PAAS模式
  如果是自动模式，需要设置特定的域名使用对应的模式  

参考：    
[[xxnet php搭建教程]]    
[[xx-net教程-使用OpenShift搭建php空间]]