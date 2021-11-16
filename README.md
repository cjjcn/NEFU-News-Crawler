# NEFU-News-Crawler
东北林业大学新闻爬虫

目前支持抓取的内容列表

| 网站名称                                 | 网址                                    |
| ---------------------------------------- | --------------------------------------- |
| 东北林业大学新闻站综合新闻               | https://news.nefu.edu.cn/dlyw.htm       |
| 东北林业大学新闻站人物专栏               | https://news.nefu.edu.cn/xyrw.htm       |
| 东北林业大学信息与计算机工程学院新闻中心 | https://icec.nefu.edu.cn/index/xwzx.htm |
| 东北林业大学机电工程学院                 | https://cmee.nefu.edu.cn/index/xyxw.htm |



## Commands

### 信息学院

`scrapy crawl icec -o titles.json`

### 内容

`scrapy crawl icec_content -o titles.json`

### 机电学院

`scrapy crawl cmee_content -o titles.json`

### 东林新闻主站

`scrapy crawl news -o titles.json`

### 东林新闻站人物栏目

`scrapy crawl people -o titles.json`

