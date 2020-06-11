
# github 常用命令
* watch：会持续收到该项目的动态

* fork:复制项目到自己的github仓库

* star:点赞

* clone:将项目下载到本地

* follow：关注你感兴趣的作者，会收到他们的动态

## in 关键词限制搜索范围
        xx 关键词   in:name 或description或readme

       xx in:name  项目名称包含XX的

       xx in:description  项目描述中包含xx的

       xx  in:readme  项目readme文件中包含xx的

## 组合使用  项目名称或者description中包含tesseract
       
        stars 或fork 数量关键词去查找
          xx 关键词 stars 通配符   ：> 或者 ：<= 
          区间范围数字  数字1..数字2
          
* 查找stars数大于等于5000的springcloud
```
springcloud stars:>=5000
```

* 查找fork 数大于5000的springcloud项目
```
springcloud fork:>=5000
```


## 组合使用    查找fork在100到200并且stars 数在 80 到100 之间的springcloud项目

```
springcloud fork:100..200 stars:80..100
```

## awesome加强搜索
        awesome  释义为极好的，了不起的    此关键字一般用来搜索优秀的框架

* 搜索 redis相关的优秀项目
```
awesome redis
```

* 高亮显示某一行代码   地址后面+#行号   如高亮显示第18行
* 高亮显示  多行   地址#L数字1-L数字2   如高亮显示  第18行到第35行

## 项目内搜索
 * 使用快捷键t  可快速查找（类名）
        
        
## 搜索某个区域的大佬（活跃度高的人）
        如查找上海区域的java  大佬
```
location:shanghai language:java
```
