简单的介绍mvc

## 程序 = 算法 + 结构
应该是老道,80年之前提到的概念

最关键的地方在于当时,没有v 【也就那两年,试验机】

## mvc , gui 与 面向对象
73年,第一代gui问世   奥托

之后,立刻开发一款更适合gui的语言 也就是 初代面向对象语言 【应该是第二个,用初代写的gui】


联系上诉内容,mvc的内容已经很清晰了

m 结构 c 算法【特质gui交互】 v gui ,他们隶属于三大块,就是最早期逻辑上的解耦

## 实例
1. asp 项目
大学期间,维护的项目,核心是实现

包含以下内容,asp中嵌入sql,大量重复使用,后续无法对sql进行优化  

图

此处,请求连接是在视图逻辑渲染完后,在进行关闭的
2. jsp 项目
图 网上到处都是

最核心的一点是模型与视图分离,指查询数据后,数据结构缓存到内存中,不在占用连接

注:
    此时,前端组件化包括html初始化,当时jsp流行,jsp渲染时,可以获取初始化数据

    对于这种数据如何初始化,早期是html展示 【easyui,下select,table,允许带有options或tr进行初始化】

    后期这种风格逐步被代替 
    
        1. 跟ajax初始化重复   
        2. data展开,占流量    【特质将data存在js或input中的优化】
        3. 每个组件初始化方式不一样  【需要记视图,如select/option,table/tr】

3. 前端 mv* 项目
    可以叫服务分离,也可以叫b/s与c/s 同化

    断网情况下,c/s依然能打开,而b/s,理论上也可以 【离线网站和离线操作】


