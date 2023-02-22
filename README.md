# OneApp
基于oneWeb生成后端页面的同时生成UniAPP的移动端代码，通过Hbuilderx进行打包各种APP程序。
OneAPP中框架部分采用Hbuilderx编译成app，内部嵌入web页面，通过访问web页面方式。
实现APP容器功能，页面都是采用内嵌页面导航方式，不是实际打包在APP程序中。
oneapp的动态页面部分放在oneweb服务端，由oneFast通过调用OneApi方式后端页面。更改页面无需编译客户端app，减少打包次数，可以通过Hbuilderx后端生成页面部署。
     实现扫码、统一推送、支付等公用功能框架。
