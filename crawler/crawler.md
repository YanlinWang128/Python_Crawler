# PythonCrawler
## 爬虫(crawler)基础
### 相关概念
* **聚焦爬虫** 只爬取自己需要的内容,会对抓取的内容进行筛选和处理,尽量保证只抓取和需求相关的网页信息
* **通用爬虫** 将网页下载到本地,形成一个互联网内容的镜像备份



### 工具
* Python3.6 开发环境
* Pycharm 2017 professional
* 虚拟环境 virtualenv / virtualenvwrapper

### 常用请求
* get请求: 只从服务器获取数据下来,并不会对服务器资源产生任何影响的时候用get请求
* post请求: 向服务器发送数据(登录),上传文件等,会对服务器资源产生影响的时候
