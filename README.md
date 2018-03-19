# MovieSpider-By-CSharp
A teamwork for c# practice.

> C#课程实训作业   
> 基于正则表达式实现的爬取固定页面的电影爬虫    
> 目前可筛选电影，分类缓存信息至本地，爬取成功条目率50%(受限于各种神奇的格式)    
> 欢迎大家批评指正  

`创建于2016年11月29日`  

---

## 开发相关：  
   <br>
**开发团队：**  

* [轮子(LunziQwQ)](https://github.com/LunziQwQ)　　　　------除了正则表达式之外的所有工作   
* [晓新(xxsgithub)](https://github.com/xxsgithub) 　　　　------提供了已测试的JS语言的正则表达式  

**工具及框架：**

* IDE:`VS2015`  
    
---

## 软件说明：  

   这是爬取固定页面的简单爬虫，目标网址为[“电影港”](http://66ys.cc)。  
   设置深度可以限定爬取数量，设置延时防止网页反爬虫或网络部分问题，建议延时值>=50。  
   缓存数据保存在当前用户的Document/MovieCache下，根据类别用文件夹分开。  
   由于单线程阻塞UI渲染，开始爬取时界面会出现类似无响应的现象，请耐心等待。  
   网络状态若显示Failed，有可能是您的网络连接不通，也可能是目标网址出现了问题。   
 
---
   That's all, thanks. 
