程序介绍：

1.本程序以京东领取优惠券为例学习requests模块，仅作交流学习使用，请勿用于
  其它非法用途，程序作者不承担任何法律责任。

2.领券功能：
   2.1 优惠券链接存放在urls.txt，一行一个链接。
   2.2 用户cookie存放在cookies.txt，一行一个cookie。（cookie需要自己浏览器登录
       账户后自行提取，这里不提供。若cookie长度超出1行，请考虑使用隐身模式登录
       提取cookie，或者手动删除cookie中一些不必要的内容）
   2.3 使用前请先关闭fiddler软件，否则会报出SSL错误

3.京豆兑换券功能：
   3.1 用户密码存放在password.txt中，并保证与cookies.txt的数目和顺序相同，否则报错

4.软件可选择单个用户执行亦可选择全部用户，可单次提交亦可循环提交，定时提交等。

6.返回领取结果