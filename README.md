# 抽奖游戏系统
使用外部的抽奖游戏网站的开奖接口进行开奖，网站使用php搭建，游戏使用java运行。

代码还没上传，服务器里面游戏还在运行，等游戏不运行了，我把服务器里面的代码拿出来上传。

截图看文件夹：前后台截图

开奖的号码来自酷狗直播的怪物塔防游戏。

使用java调用接口获取开奖号然后用php网站展示出来。

用户在php网站进行下注进行游戏。

推荐使用负载均衡的服务器，不然游戏容易卡死。

window上如果使用php-cgi，麻烦写一个批处理程序定期的重启php-cgi，因为php-cgi不稳定，反正我是这样做的，虽然肯定有更好的解决方案。

我也想用Linux，然后用更好的解决方案，可是客户买的服务器是win。
