<p>本项目是用go语言写的抓取股票数据爬虫。</p>

## 特点

1. 使用go协程、channel、数据库连接池特性，30s秒内抓取所有股票数据
2. 程序执行时进度条显示
3. 可以自定义时间段查询
4. 请求执行结果记录日志

## 使用方式：

```go
//默认抓取近七天数据
go run main.go

//抓取自义定时间段数据
go run main.go -start=20200225 -end=20200325
```

![image](http://123.207.71.77/wp-content/uploads/2020/03/20200326161150_64608.png)
