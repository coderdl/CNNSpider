# CNNSpider
1.直接运行文件即可进行爬虫，需要安装第三方库goose

2.对爬取内容进行修改，可以直接修改Config.py文件中的KEYWORDS
eg.
KEYWORDS = ['China','new'，'fair']

3.爬取结果分文件保存在各自的文件价当前目录下
文件夹名即KEYWORDS中的关键词
文件名为文件标题，如果文件标题有特殊符号，会只以标题中的文字来命名

4.爬取结果以json格式保存进文件，读取文件后可以直接转为json格式进行操作
字典中key的含义
author-作者
keywords-文章的关键字
source-文章来源
section-文章所属分类
headline-文章标题
time-文章更新时间
url-文章的网址
content-文章的内容

5.单线程程序，所以效率较低

6.每个文件夹下不会有重复文件出现，但是文件夹之间可能会有重复文件出现
