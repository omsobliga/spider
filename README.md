spider
======

网络爬虫

参数说明：

-u 指定爬虫开始地址

-d 指定爬虫深度，默认为2

--thread 指定线程池大小，多线程爬取页面，可选参数，默认10

--dbfile 存放结果数据到指定的数据库（sqlite）文件中，默认spider.py

--key 页面内的关键词，获取满足该关键词的网页，可选参数，默认为所有页面

启动文件：spider.py
