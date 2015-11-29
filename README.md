# daka
登录网站并打卡（或领金币等）。目前实现了百度贴吧签到、lifevc签到、沪江部落领金币及蚂蜂窝打卡领蜂蜜。

# 第三方依赖
1. BeautifulSoup

# 使用
1. 在文件`user_config.ini`中配置对应网站的用户名密码
2. 运行samples/run.py

# 扩展
1. 导入Site模块：`from Site import Site`
2. 新建类继承Site
3. 查看网站登录逻辑，编写对应的request header, request data和对response的解析方法。调用`_login`方法。
4. 查看网站的打卡逻辑，编写对应的request header, request data和对response的解析方法。调用`_daka`方法。

# TO-DO
1. 优酷
2. 淘宝
3. 其他？
