# aboutDjango

for newbie Django developer 

## 环境准备

### F&Q：

1.如何在Python 3 环境的Mac中打通Django 2.0和MySQL并正确使用pycharm启动服务器？

常规方法安装python

pip install django == 2.2.14

pip install mysqlclient

点击右上角项目环境设置，进入Edit Configurations:

在环境（Environment）中的Environment variables加入：

```py
DYLD_LIBRARY_PATH=/usr/local/mysql/lib/
```

注意分号分隔
