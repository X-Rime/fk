# fk
# python期末项目
- 代码GithubURL：https://github.com/camaxjj/python
- pythonanywhereURL：http://xiongxionghandsome.pythonanywhere.com/

# 项目简介
- 简易商品搜索系统
- 项目所用技术
    1. python, flask, sqlite, javascritp, html, css, ajax
- 项目文件结构
    1. app.py   项目入口文件
    2. data.db  项目数据库
    3. templates    项目模板文件
    4. static   项目所用框架及静态文件
- 项目环境
    1. windows10
    1. Python3.7
    2. Flask1.1
    3. sqlite3
- app.py 入口文件介绍
    1. 函数 login 登录模板
    2. 函数 login_ 登录逻辑处理
    3. 函数 index   搜索首页及逻辑处理
    4. 函数 dingdan  订单页面及逻辑处理
    5. 函数 tuihuan   退换模板
- templates 模板文件介绍
    1. login.html  登录页面
    2. index.html  搜索页面
    3. dingdan.html  订单页面
    4. tuihuan.html  退换页面
- static 静态文件介绍
    1. images  网址图片文件
    2. lib/layui layui框架
    3. jquery    jq框架

# 业务功能介绍
- 搜索页面
    1. 根据搜索词搜索出包含关键词得所有商品，使用GET模式请求
- 订单管理
    1. 可以根据关键词搜索出相关产品
    2. 可以添加产品进入购物车，并实时计算出总价， 并保存到cookie, 刷新不丢失
    3. 可以统一打包 并下单处理
 - 退换货管理
    1. 简易得退换处理
