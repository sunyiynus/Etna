本周面试题。它是50万年薪分类器的一部分。类似的几个问题，如果回答得好，就定位在50万以上年薪。如果能够很容易的搞定这个问题，年薪还不到50万的，可以来我们这里试试。感兴趣的可以讨论一下。（下周要换新题了）

某电话服务商在重庆市有2000万用户，平均每人每天最多打5个电话。电话交换机会生成很多“话单文件”，这是一个文本文件，里面包含几百万行文本，话单文件的每一行包含几个信息：主叫号码、被叫号码、通话开始时间、通话时长。

功能需求：

1. 下载并转储话单文件

编写一个服务器上运行的后台程序，每天晚上从话交换机上下载话单文件，每个交换机每天生成一个话单文件，一共大约100个交换机。然后把这些话单文件里面的通话信息经过一些处理之后，新内容写到你自己设计的文件格式中。

2. 实现通话详单查询功能。

少数用户会不定期要求查询近期通话详单。例如：查询进1个月的通话详单，最近2个月的通话详单，等等。最多支持查询近3个月的通话详单。要求：每小时查询电话详单不超过2000次负荷下，每次查询时间不超过1秒。

3. 实现话费月结功能。

每个月3号，为每个用户生成一个话费单文件，包括：上过月通话时长，以及需缴纳的话费。话费按照0.10元/分钟计算。要求总处理时间不超过10小时。

要求：只使用C/C++语言（或者golang）和语言提供的标准库函数，不实用任何第三方组建。

1、如何解决这个问题？给出技术方案主要思路。2、大概需要多少代码量？写代码包括调试需要多少时间？3、在一台普通服务器上运行，服务器需要什么配置，才能够支持这个应用？
