# release
>  发布可直接运行版本(无需源码)，直接在本页面下载可执行文件，再安装好数据库就可以运行



### 安装Mysql，3分钟

- 从[官网](http://dev.mysql.com/downloads/)下载



### 安装Elasticsearch，5分钟

- [下载](https://www.elastic.co/downloads/elasticsearch) 2.xx版本，解压出文件夹
- 在unix环境中，运行 `bin/elasticsearch`, 在windows运行 `bin\elasticsearch.bat` 


### 下载可执行文件，2分钟

根据运行环境选择下载

- [linux_amd64.zip](http://obu2kw0g0.bkt.clouddn.com/linux_amd64.zip)
- [linux_386.zip](http://obu2kw0g0.bkt.clouddn.com/linux_386.zip)
- [windows_amd64.zip](http://obu2kw0g0.bkt.clouddn.com/windows_amd64.zip)
- [windows_386.zip](http://obu2kw0g0.bkt.clouddn.com/windows_386.zip)
- [darwin_amd64.zip](http://obu2kw0g0.bkt.clouddn.com/darwin_amd64.zip)
- [darwin_386.zip](http://obu2kw0g0.bkt.clouddn.com/darwin_386.zip)

目录结构

```shell
├── api                      对外提供API服务
│   ├── api                  可执行文件
│   └── config               配置文件
│       └── api.conf
├── crawl                    抓取活跃infohash于metadata
│   ├── config				配置文件
│   │   └── crawl.conf		 
│   └── crawl				可执行文件
├── site                     网站前端代码
└── storage					从资源库抓取资源(xunlei)
    ├── config				配置文件
    │   └── storage.conf
    └── storage				可执行文件
```



### 常见问题

- crawl运行时报错，参考[crawl主页](https://github.com/btlike/crawl)

  ​
