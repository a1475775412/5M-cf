# 5秒盾
5秒盾代码,PHP网站仿百度云加速浏览器5秒安全检查,可有效防止cc攻击
一个网站能否正常访问对于这个网站SEO有很大的影响
隔一二天不能访问，网站的排名收录会掉的很厉害而且影响以后
正因为这样，出现了很多网络黑客专门以攻击他人网站谋生
今天就给大家分享一个能有效防止一下小CC.用过百度云加速服务的网站都知道，在第一次打开后都会跳出
“浏览器安全检查中”等待5秒倒计时，才正常进入网站主页。
这样可以有效防止CC攻击。在全局引入jiance.php即可，
如：include 'jiance.php';
倒计时完毕后跳转主页并写cookie，第二次访问就不再显示。
就直接把jiance.php文件放网站目录，然后去模版文件module.php添加下面的调用代码
[Test小林] http://blog.mcxhz.cn
