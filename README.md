# xianyu
全站爬虫：使用scrapy-crawl全站爬虫，爬取闲鱼二手交易网站所有二手物品发帖人以及发帖地址。
百万+ 数据
目的是为后期统计闲鱼地区活跃度，以及任务活跃度提供数据支持。
spider文件比较简单，因为是爬取非详情页信息，主要在于链接rule的提取，因为闲鱼链接真的好乱
支持直接写去数据库
自动更换请求头
自动限速
