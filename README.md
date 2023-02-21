# x-render

打开博客项目：https://github.com/Misaka-blog/x-render
点击“Use this template”按钮，创建一个新的私库

修改config.json中的第14、52、69、100、128和157行，修改自己的UUID（UUID生成器：https://www.uuidgenerator.net/ ）。在第28和108行修改vmess路径，在第14和80行修改vless路径，在第32和136行修改trojan路径，在第36和165行修改shadowsocks路径。修改app.js的38和123行修改哪吒参数
打开Render官网：https://www.render.com ，点击“Sign in”进行注册。如有账户登录即可

点击“New Web Service”创建一个Web Project

可以连接自己的GitHub账户。也可以使用我的公开库地址。选择项目

输入项目名称，选择服务器区域。机器类型选择Free

等待1-3分钟部署，复制项目链接备用

节点配置如下：

协议：Vmess / Vless / Trojan / Shadowsocks

地址：appname.onrender.com

端口：443

UUID/密码：自动生成或设置的uuid变量内容

额外ID：0

Shadowsocks加密方式：chacha20-ietf-poly1305

传输协议：ws

伪装域名：appname.onrender.com

路径：/vmess（/vless、/trojan、/shadowsocks）或设置的VMESS_WSPATH（VLESS_WSPATH、TROJAN_WSPATH、SS_WSPATH）变量内容

传输安全：TLS

跳过证书验证：true或false都可以
