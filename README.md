
# django-wshop 微商城



没有发现合适的django shop 微商城的开源项目，准备着手做一个

计划先实现一个简单的功能


- 购物车
- 用户中心
- 产品管理
- 库存管理
- 订单管理
- 微信支付
- 余额支付

**一个版本预计10月底发布**

>后续考虑 PC 版本 ，微信小程序和　APP　

后台使用 django admin 来搭建，使用 material 项目做了美化

前台界面预览：

![](https://i.loli.net/2017/07/28/597af6aba23be.jpg)


![](https://i.loli.net/2017/07/28/597af6d4eb421.jpg)

后台界面预览：

![](https://i.loli.net/2017/07/20/59701f1d59c22.jpg)

material 不能使用第三方组件，费了好大劲加上了富文本


![](https://i.loli.net/2017/07/20/59707e4d15d78.jpg)



    大家自行clone，然后运行，我这里简单介绍clone下来后，安装方面需要注意的问题

    首先需要安装相关数据库，我这里用mysql做示范(鉴于大家的普遍使用), ubuntu安装参考, 然后创建一个名为django-wshop的数据库
    (可选)redis 安装， 安装参考，然后启动redis
    新建一个虚拟环境，然后安装相关模块pip install -r requirements.txt
    初始化表python manage.py migrate
    最后运行python manage.py runserver








