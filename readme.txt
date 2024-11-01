=== WPUPYUN又拍云云存储 ===

Contributors: laobuluo
Donate link: https://www.lezaiyun.com/donate/
Tags:WordPress对象存储,WordPress加速,WordPress 又拍云存储, 又拍云WordPress,又拍云对象存储
Requires at least: 4.5.0
Tested up to: 6.5.3
Stable tag: 3.9.2
Requires PHP: 5.6
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

== Description ==

WordPress又拍云云存储插件（简称:WPUPYUN），基于又拍云云存储与WordPress实现静态资源到又拍云对象存储中。提高网站项目的访问速度，以及静态资源的安全存储功能。 公众号： 老蒋朋友圈。


## 插件特点

1. 新增支持又拍云图片编辑 设置水印、编辑图片、压缩WEBP等
2. 支持已有图片编辑功能
3. 支持自定义域名设置 可设置多级目录
4. 支持一键替换静态本地化至对象存储远程URL
5. 支持一键禁止缩略图
6. 支持自定义任意对象存储目录，一个存储桶可以多网站
7. 支持自动文件重命名
8. 支持本地和对象存储分离和同步
9. 优化重构加速上传

又拍云插件安装方法：[https://www.laobuluo.com/2620.html](https://www.laobuluo.com/2620.html)

## 网站支持

* [老部落](https://www.laobuluo.com/ "老部落")

* [老蒋部落](https://www.itbulu.com/ "老蒋部落")

* [乐在云](https://www.lezaiyun.com/ "乐在云")

* 欢迎加入插件和站长微信公众号：老蒋朋友圈（公众号）

== Installation ==

* 1、把WPUPYUN文件夹上传到/wp-content/plugins/目录下<br />
* 2、在后台插件列表中激活WPUPYUN<br />
* 3、在左侧【WP又拍云设置】菜单中输入又拍云存储空间账户信息。<br />
* 4、设置可以参考：https://www.laobuluo.com/2620.html

== Frequently Asked Questions ==

* 1.当发现插件出错时，开启调试获取错误信息。
* 2.我们可以选择备份对象存储或者本地同时备份。
* 3.如果已有网站使用WPUPYUN，插件调试没有问题之后，需要将原有本地静态资源上传到又拍云存储中，然后修改数据库原有固定静态文件链接路径。、
* 4.如果不熟悉使用这类插件的用户，一定要先备份，确保错误设置导致网站故障。

== Screenshots ==

1. screenshot-1.png

== Changelog ==

= 3.9.2 =
* 兼容最新WP6.2测试

= 3.9 =
* 兼容最新WP6.1测试

= 3.8 =
* 兼容最新WP6.0测试

= 3.7 =
* 兼容最新WP5.9.3测试

= 3.6 =
* 兼容最新WP5.7测试

= 3.5 =
* 兼容最新WP测试
* 细节文档调整

= 3.4 =
* 兼容最新WP测试
* 细节文档调整

= 3.3 =
* 解决图片编辑自定义规则问题
* 

= 3.2 =
* 更新插件前端 体验更友好
* 修复部分细节问题 文档说明

= 3.1 =
* 兼容测试
* 定稿又拍云对象存储正式版和图片处理文档说明

= 2.2 =
* 兼容WP5.4.2测试
* 微调部分说明文档便于引导用户使用

= 2.1 =
* 提高编辑图片效率
* 新增又拍云图片编辑功能，可压缩图片和水印自定义适配官方文档
* 新增支持自定义任意远程目录，可多站点使用一个云存储空间

= 2.0 =
* 重构插件代码 提高优化性能
* 新增随机重命名、禁止缩略图

= 1.3.1 =
* 兼容WP5.4.1版本测试

= 1.3.1 =
* 兼容WP5.4版本
* 优化部分前端，准备重构代码

= 1.2 =
* 解决删除媒体库不同步删除问题
* 重新调优部分代码

= 1.1 =
* 解决WordPress升级5.3之后图片处理方式问题
* 调试兼容WP5.3和老版本WP

= 1.0 =
* 完成又拍云对象存储自动同步WordPress图片静态文件插件；
* 解决图片重复上传和超时问题
* 解决Apache默认环境出现超时HTTP上传错误
* 解决同步本地和又拍云存储图片错误问题

== Upgrade Notice ==
* 