blog
目的：掌握单机WEB系统架构

色调：


admin console思路：
1、div+css布局；
2、用的比较经典的方式，公共模块复用，header.jsp,menuBar.jsp,footer.jsp。这种方式还是不够好，每个页面的公共区域都要拷贝一次；
3、没有用sitemesh进行页面组装；
4、有想过参考先前公司的设计，太复杂（自定义标签，后端获取正文部分的response后，组装到模板返回），木有时间搞；
5、海投网，kindle后台管理页面做的挺好，他们是怎么做到的？DIV+CSS架构不容易分析到底怎么实现的。
6、以后再不断完善吧


2015-2-5
1、博文管理，文章列表，自己实现列表还是使用表格插件？整页刷新的方式，还是ajax方式？
点击浏览器后退，没必要列表第几页都记录上，参见Amazon -> 管理我的kindle，那样的话就太麻烦了；因此，也就没必要整页刷新了，选择ajax方式，当然也就用插件了，
自己实现太耗费时间了。选用jQuery DataTables。




