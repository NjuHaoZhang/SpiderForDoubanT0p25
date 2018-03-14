### 1. douban1.py
这是一个基于原生python，基于request库，利用字符串处理的爬虫，实现的效果是：爬去豆瓣的2500条记录，找出TOP25最受用户喜欢的电影，并取出每一个电影的特征元素
### 2. douban2.py
这是一个分析了URL的特点后，支持批量下载网页
### 3. douban3.py
这是一个加入了缓存的爬虫，如果曾经下载过就直接去缓存中找HTML文件，否则下载。可以提高爬虫的效率
### ParseJSSpider.py
这是一个针对`http://zhizhizhi.com/gn/1/`的网页爬虫，这个网页的特点就是：纯JS动态生成，直接爬取的是JS文件，本程序加入了`selenium.webdriver`,模拟浏览器解析生成一个HTML文件，之后再基于DOM进行解析。
