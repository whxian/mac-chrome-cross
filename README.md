# mac-chrome-cross
mac上设置新版chrome浏览器跨域
___
设置方法

打开一个新的可跨域的chrome窗口实现方法：

1. 打开终端

2. 输入下面的命令( 需要替换路径中的yourname )

`open -n /Applications/Google\ Chrome.app/ --args --disable-web-security  --user-data-dir=/Users/yourname/MyChromeDevUserData/`

注意

网上有些文章--user-data-dir参数后面没有添加文件夹名，是设置不成功的。

发现

第一次打开chrome有黄色背景色的“--disable-web-security”相关的提示，说明浏览器设置跨域成功。

再次用执行上面的命令行时，不会再有相关提示了，但是还是能跨域的！

 

参考来源：

http://www.cnblogs.com/laden666666/p/5544572.html
