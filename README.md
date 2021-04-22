网上订餐系统--后端部分

本系统共用三个客户端，用户端、商家端和骑手端

本系统是基于SpringBoot+Vue的前后端分离架构，使用MySQL+Redis数据库,结合Shiro安全框架，MyBatis持久层框架
前端采用axios请求，前后端采用Restful接口风格对接，使用json数据格式交互.

三个客户端之间采用Websocket通讯协议进行实时交互，页面UI上用户端和骑手端采用Vant，商家端使用ElementUI.

项目部署上采用Doker虚拟化部署在自己的阿里云上，结合Nginx、Haproxy和keepalived,从数据库到后端、前端均采用多节点负载均衡策略部署。

整个项目用的都是目前主流的技术，覆盖前后端各个技术的基础，从数据库，到后端，再到前端，再部署上云，只需这一个项目即可了解掌握整个项目的开发流程及各种细节！

 :raised_hand: 手机移动端用户端地址（电脑端打开请按ctrl+shirt+i进入浏览器调试模式，调成手机大小模式）
 http://106.14.242.100:8090/#/user

 :raised_hand: 需要前端vue项目和sql文件的前往：
 http://106.14.242.100:8090/#/UploadRes

如有疑问，请联系qq:1058298031

本人毕设项目，还请多多指教！请拉取代码的点点star！！谢谢！

**移动用户端主要界面：**

![用户端](https://images.gitee.com/uploads/images/2020/0306/171925_a7ceb550_5465839.png "屏幕截图.png")
![用户端](https://images.gitee.com/uploads/images/2020/0306/172026_8fdb4e68_5465839.png "屏幕截图.png")
![用户端](https://images.gitee.com/uploads/images/2020/0306/171908_0bdd2177_5465839.png "屏幕截图.png")

**移动骑手端主要界面：**

![骑手端](https://images.gitee.com/uploads/images/2020/0306/171714_d6ed403e_5465839.png "屏幕截图.png")
![骑手端](https://images.gitee.com/uploads/images/2020/0306/171747_d333a38b_5465839.png "屏幕截图.png")

**pc商家管理端主要界面：**

![商家端](https://images.gitee.com/uploads/images/2020/0306/171814_03e922d5_5465839.png "屏幕截图.png")
![商家端](https://images.gitee.com/uploads/images/2020/0306/171846_605cfba4_5465839.png "屏幕截图.png")

