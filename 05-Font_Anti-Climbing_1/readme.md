### 声明：
&emsp; 本次实践参考公众号"老王的小船"的文章"Python爬虫: 字体反爬".

### 目标：
&emsp; 处理猫眼电影票房排行字体的反爬，实则为数字数据的反爬处理.

### 前言：
&emsp; 字体反爬是一种常见的反爬技术，例如猫眼电影票房、汽车之家、天眼查等网站。上述网站采用了自定义的字体文件，在浏览器上显示正常，爬取下来不是乱码就是其他字符。而采用自定义文件是CSS3的新特性，详情参考：http://www.w3scholl.com.cn/css3/css3_font.asp. 
### 分析
&emsp; 具体的分析过程可以查看链接:https://news.html5.qq.com/share/5775782442559298943?url=http%3A%2F%2Fkuaibao.qq.com%2Fs%2F20181013B1L65N00   
(注意：文章链接在QQ浏览器，可以发送至手机后再查看；或者关注作者查看原始文章)