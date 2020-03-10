=== REST API TO WeChatBlog ===
Contributors: nizerin
Donate link: https://www.iacblog.com/
Tags: 微信小程序,rest,api,json
Requires at least: 4.7.1
Tested up to: 5.2.4
Stable tag: 1.6.1
Requires PHP: 5.6
License: MIT
License URI: https://www.mit-license.org/

== Description ==

为微信小程序、app提供定制化WordPress REST API json 输出.

详细介绍： <a href="https://www.iacblog.com/">https://www.iacblog.com/</a>

最新插件源代码更新地址：
<a href="https://github.com/NiZerin/rest-api-to-wechatblog">https://github.com/NiZerin/rest-api-to-wechatblog</a>



== Installation ==

1. 上传 `rest-api-to-wechatblog`目录 到 `/wp-content/plugins/` 目录
2. 在后台插件菜单激活该插件

== Frequently Asked Questions ==

详细介绍： <a href="https://www.iacblog.com/">https://www.iacblog.com/</a>


== Screenshots ==

1.设置
2.专业版
3.微信小程序

== Changelog ==

= 1.6.1=

（1）加入视频和插屏广告
（2）修复“猜你喜欢”的一处bug
  (3)  函数get_client_ip改名为ram_get_client_ip ，避免和其他的插件重名冲突

= 1.6.0=
（1）调整滑动图片文章的顺序，按设置的id顺序排序
（2）加入微信广告配置
  (3)  完善分类和后台设置

= 1.5.7=
修复登录的问题

= 1.5.6 =
修复激活报错的问题，解决插件不兼容的问题。

= 1.5.5 =
修复插件报错“$ is not a function”

= 1.5.4 =
修复无法获取默认海报地址的问题

= 1.5.3 =
修复与古腾堡编辑器无法兼容的问题

= 1.5.2 =
修复点赞及赞赏头像显示的问题

= 1.5.1 =
调整微信支付换算

= 1.5 =
(1）增加对昵称里特殊字符的过滤。（2）评论的数量过滤掉未通过审核的评论。（3）修复获取文章是否点赞的bug。（4）增加更新用户信息，在用户信息里增加角色信息。（5）修复如果腾讯视频过多导致的加载失败。（6）在后台用户显示头像。（7）调整支付代码，解决和其他插件使用腾讯官方支付示例代码引起的冲突。（8）评论增加审核选项

= 1.1 =
修复新用户无法授权登录的问题。

= 1.0 =
修复wordpres升级5.0后插件与古藤堡编辑器无法兼容的问题。

= 0.8 =
* 初始版本

== Upgrade Notice == 

如果你曾经安装过wp-rest-api-for-app 请先卸载此插件,REST API TO WeChatBlog无法与该插件同时使用,但会保持并加绒该插件的功能.
