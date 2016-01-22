# Summary

* 参考资料汇总

# 目录
* [前言](eBook/preface.md)

## 第一部分：学习 Go 语言

* [Go 语言的起源，发展与普及]()
	*  [起源与发展](eBook/01.1.md)
	*  [语言的主要特性与发展的环境和影响因素](eBook/01.2.md)
* 第2章：安装与运行环境
	*  [平台与架构](eBook/02.1.md)
	*  [Go 环境变量](eBook/02.2.md)
	*  [在 Linux 上安装 Go](eBook/02.3.md)
	*  [在 Mac OS X 上安装 Go](eBook/02.4.md)
	*  [在 Windows 上安装 Go](eBook/02.5.md)
	*  [安装目录清单](eBook/02.6.md)
	*  [Go 运行时（runtime）](eBook/02.7.md)
	*  [Go 解释器](eBook/02.8.md)
* 第3章：[编辑器、集成开发环境与其它工具](eBook/03.0.md)
	*  [Go 开发环境的基本要求](eBook/03.1.md)
	*  [编辑器和集成开发环境](eBook/03.2.md)
	*  [调试器](eBook/03.3.md)
	*  [构建并运行 Go 程序](eBook/03.4.md)
	*  [格式化代码](eBook/03.5.md)
	*  [生成代码文档](eBook/03.6.md)
	*  [其它工具](eBook/03.7.md)
	*  [Go 性能说明](eBook/03.8.md)
	*  [与其它语言进行交互](eBook/03.9.md)

## 第二部分：语言的核心结构与技术

* 第4章：基本结构和基本数据类型
	*  [文件名、关键字与标识符](eBook/04.1.md)
	*  [Go 程序的基本结构和要素](eBook/04.2.md)
	*  [常量](eBook/04.3.md)
	*  [变量](eBook/04.4.md)
	*  [基本类型和运算符](eBook/04.5.md)
	*  [字符串](eBook/04.6.md)
	*  [strings 和 strconv 包](eBook/04.7.md)
	*  [时间和日期](eBook/04.8.md)
	*  [指针](eBook/04.9.md)
* 第5章：[控制结构](eBook/05.0.md)
	*  [if-else 结构](eBook/05.1.md)
	*  [测试多返回值函数的错误](eBook/05.2.md)
	*  [switch 结构](eBook/05.3.md)
	*  [for 结构](eBook/05.4.md)
	*  [Break 与 continue](eBook/05.5.md)
	*  [标签与 goto](eBook/05.6.md)
* 第6章：[函数（function）](eBook/06.0.md)
	*  [介绍](eBook/06.1.md)
	*  [函数参数与返回值](eBook/06.2.md)
	*  [传递变长参数](eBook/06.3.md)
	*  [defer 和追踪](eBook/06.4.md)
	*  [内置函数](eBook/06.5.md)
	*  [递归函数](eBook/06.6.md)
	*  [将函数作为参数](eBook/06.7.md)
	*  [闭包](eBook/06.8.md)
	*  [应用闭包：将函数作为返回值](eBook/06.9.md)
	* 0 [使用闭包调试](eBook/06.10.md)
	* 1 [计算函数执行时间](eBook/06.11.md)
	* 2 [通过内存缓存来提升性能](eBook/06.12.md)
* 第7章：[数组与切片](eBook/07.0.md)
	*  [声明和初始化](eBook/07.1.md)
	*  [切片](eBook/07.2.md)
	*  [For-range 结构](eBook/07.3.md)
	*  [切片重组（reslice）](eBook/07.4.md)
	*  [切片的复制与追加](eBook/07.5.md)
	*  [字符串、数组和切片的应用](eBook/07.6.md)
* 第8章：[Map](eBook/08.0.md)
	*  [声明、初始化和 make](eBook/08.1.md)
	*  [测试键值对是否存在及删除元素](eBook/08.2.md)
	*  [for-range 的配套用法](eBook/08.3.md)
	*  [map 类型的切片](eBook/08.4.md)
	*  [map 的排序](eBook/08.5.md)
	*  [将 map 的键值对调](eBook/08.6.md)
* 第9章：[包（package）](eBook/09.0.md)
	*  [标准库概述](eBook/09.1.md)
	*  [regexp 包](eBook/09.2.md)
	*  [锁和 sync 包](eBook/09.3.md)
	*  [精密计算和 big 包](eBook/09.4.md)
	*  [自定义包和可见性](eBook/09.5.md)
	*  [为自定义包使用 godoc](eBook/09.6.md)
	*  [使用 go install 安装自定义包](eBook/09.7.md)
	*  [自定义包的目录结构、go install 和 go test](eBook/09.8.md)
	*  [通过 Git 打包和安装](eBook/09.9.md)
	* 0 [Go 的外部包和项目](eBook/09.10.md)
	* 1 [在 Go 程序中使用外部库](eBook/09.11.md)
* 第10章：[结构（struct）与方法（method）](eBook/10.0.md)
    * 10.1 [结构体定义](eBook/10.1.md)
    * 10.2 [使用工厂方法创建结构体实例](eBook/10.2.md)
    * 10.3 [使用自定义包中的结构体](eBook/10.3.md)
    * 10.4 [带标签的结构体](eBook/10.4.md)
    * 10.5 [匿名字段和内嵌结构体](eBook/10.5.md)
    * 10.6 [方法](eBook/10.6.md)
    * 10.7 [类型的 String() 方法和格式化描述符](eBook/10.7.md)
    * 10.8 [垃圾回收和 SetFinalizer](eBook/10.8.md)
* 第11章：[接口（interface）与反射（reflection）](eBook/11.0.md)
    * 11.1 [接口是什么](eBook/11.1.md)
    * 11.2 [接口嵌套接口](eBook/11.2.md)
    * 11.3 [类型断言：如何检测和转换接口变量的类型](eBook/11.3.md)
    * 11.4 [类型判断：type-switch](eBook/11.4.md)
    * 11.5 [测试一个值是否实现了某个接口](eBook/11.5.md)
    * 11.6 [使用方法集与接口](eBook/11.6.md)
    * 11.7 [第一个例子：使用 Sorter 接口排序](eBook/11.7.md)
    * 11.8 [第二个例子：读和写](eBook/11.8.md)
    * 11.9 [空接口](eBook/11.9.md)
    * 11.10 [反射包](eBook/11.10.md)
    * 11.11 [Printf 和反射](eBook/11.11.md)
    * 11.12 [接口与动态类型](eBook/11.12.md)
    * 11.13 [总结：Go 中的面向对象](eBook/11.13.md)
    * 11.14 [结构体、集合和高阶函数](eBook/11.14.md)

## 第三部分：Go 高级编程

* 第12章：[读写数据](eBook/12.0.md)
    * 12.1 [读取用户的输入](eBook/12.1.md)
    * 12.2 [文件读写](eBook/12.2.md)
    * 12.3 [文件拷贝](eBook/12.3.md)
    * 12.4 [从命令行读取参数](eBook/12.4.md)
    * 12.5 [用 buffer 读取文件](eBook/12.5.md)
    * 12.6 [用切片读写文件](eBook/12.6.md)
    * 12.7 [用 defer 关闭文件](eBook/12.7.md)
    * 12.8 [使用接口的实际例子：fmt.Fprintf](eBook/12.8.md)
    * 12.9 [格式化 JSON 数据](eBook/12.9.md)
    * 12.10 [XML 数据格式](eBook/12.10.md)
    * 12.11 [用 Gob 传输数据](eBook/12.11.md)
    * 12.12 [Go 中的密码学](eBook/12.12.md)
* 第13章：[错误处理与测试](eBook/13.0.md)
    * 13.1 [错误处理](eBook/13.1.md)
    * 13.2 [运行时异常和 panic](eBook/13.2.md)
    * 13.3 [从 panic 中恢复（Recover）](eBook/13.3.md)
    * 13.4 [自定义包中的错误处理和 panicking](eBook/13.4.md)
    * 13.5 [一种用闭包处理错误的模式](eBook/13.5.md)
    * 13.6 [启动外部命令和程序](eBook/13.6.md)
    * 13.7 [Go 中的单元测试和基准测试](eBook/13.7.md)
    * 13.8 [测试的具体例子](eBook/13.8.md)
    * 13.9 [用（测试数据）表驱动测试](eBook/13.9.md)
    * 13.10 [性能调试：分析并优化 Go 程序](eBook/13.10.md)
* 第14章：[协程（goroutine）与通道（channel）](eBook/14.0.md)
    * 14.1 [并发、并行和协程](eBook/14.1.md)
    * 14.2 [使用通道进行协程间通信](eBook/14.2.md)
    * 14.3 [协程同步：关闭通道-对阻塞的通道进行测试](eBook/14.3.md)
    * 14.4 [使用 select 切换协程](eBook/14.4.md)
    * 14.5 [通道，超时和计时器（Ticker）](eBook/14.5.md)
    * 14.6 [协程和恢复（recover）](eBook/14.6.md)
* 第15章：[网络、模版与网页应用](eBook/15.0.md)
    * 15.1 [tcp服务器](eBook/15.1.md)
    * 15.2 [一个简单的web服务器](eBook/15.2.md)
    * 15.3 [访问并读取页面数据](eBook/15.3.md)
    * 15.4 [写一个简单的网页应用](eBook/15.4.md)

## 第四部分：实际应用

* 第16章：常见的陷阱与错误
* 第17章：模式
* 第18章：[出于性能考虑的实用代码片段](eBook/18.0.md)
* 第19章：构建一个完整的应用程序
* 第20章：Go 语言在 Google App Engine 的使用
* 第21章：实际部署案例

## 附录

* A 代码引用
* B 有趣的 Go 引用
* C 代码示例列表
* D 书中的包引用
* E 书中的工具引用
* F 常见问题解答
* G 习题答案
* H 参考文献

## 索引
