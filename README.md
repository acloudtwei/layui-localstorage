# layui-localstorage

#### 介绍
一个基于前端的localstorage本地json数据库的响应式静态界面，其中前台用了bootstrap5，后台用了layui。
本次的纯静态项目是一个选修了前端设计课程的大作业，总共花费了一天的时间，主要是对localstorage本地数据库进行CRUD的操作，
并且是响应式界面，由于时间上的问题，因此很多输入没有做正则判断（比如QQ输入），还有一些业务逻辑也没有完善，界面的功能也比较少，
希望感兴趣的小伙伴可以fork或者git clone下载玩玩（感觉也没有感兴趣的，我是个菜鸡）。希望可以收获一颗star！

#### 软件架构
1. 前台部分

- bootstrap5编写响应式界面
- vue3进行循环<li>标签输出
- jquery进行部分的输入判定

2.后台部分

- layui作为主要的编写框架
- 使用了layui-mini后台模板


#### 演示站点
[点击进入演示站](http://1.14.226.170/)

#### 安装教程

1.  先git clone将本项目下载到本地
2.  之后直接先运行localStorage数据生成（请先运行此html）.html这个文件，先将localstorage数据生成到本地
3.  之后可以双击index.html进入登录首页，adminlogin.html是后台登录首页

#### 使用说明

1.  后台adminindex.html是需要在VSCode或者WebStorm上使用，否则会直接提示无法进入界面（因为设置了url验证）
2.  如果上传到服务器建议将localStorage数据生成（请先运行此html）.html改为首页界面

#### 参与贡献

1.  Fork 本仓库

#### 开发人员

本项目由Acloudtwei一人开发！
