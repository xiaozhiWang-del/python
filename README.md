# 51job_crawler

爬取51job上发布的职位信息

使用方法：
1.爬取51job网站上近两天发布的职位；主要功能是在程序运行后询问：“请输入关键词：”，你可以输入你感兴趣的方向；
2.输入之后系统会爬取51job上面发布的有关关键词的职位信息：包括职位名称、工资、发布日期、以及进入链接；
3.爬取的内容会保存在mysql数据库中，如果需要之前爬取的内容，可以进入数据库直接查询；
4.你可以根据自己的需求进行选择进入51job网站，这样会节省很多找工作的时间；
5.注意：在使用数据库时需要提前安装好，并且建立数据库和表格，这样在使用代码中才不会出错。

使用前准备：
1.安装anaconda和visual studio code 或者其他编写python工具，安装网站：https://www.anaconda.com/ ；
2.安装mysql数据库,安装网站：https://dev.mysql.com/downloads/mysql/ 可以直接在命令行使用；
3.安装好之后下载python第三方库，这些直接在命令行（cmd）中执行：pip install requests/pip install pymysql；
4.一切都准备就绪之后就可以直接使用代码了；
5.之后可以根据自己的需要对代码进行修改，爬取其他网站的内容。
