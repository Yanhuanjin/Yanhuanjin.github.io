---
title: 从零开始Django搭建Python Web项目
date: 2020-11-10 14:03:01
author: 金彦焕
categories: Python
tags:
  - Django
---

# 从零开始：Django搭建Web

Created: Oct 29, 2020 10:39 AM
Updated: Nov 10, 2020 2:01 PM

1. 在任意存储位置，新建文件夹，例如DjangoTest。

    ![1](1.png)

2. 在资源管理器地址栏键入cmd，进入命令行界面（对，直接在这里键入cmd）。

    ![2](2.png)

3. 创建虚拟环境

    这里环境名称我用test。

    ```python
    python -m venv test
    ```

4. 激活虚拟环境

    ```python
    test\Scripts\activate
    ```

    可以看到前面多了一个括号，括号内时虚拟环境的名称

    ![3](3.png)

5. 使用pip安装Django

    ```python
    pip install Django
    ```

6. 在Django中创建项目

    使用PyCharm打开DjangoTest文件夹，在Terminal窗口中输入

    ```python
    django-admin.py startproject my_blog .
    ```

7. 创建数据库

    ```python
    python manage.py migrate
    ```

8. 启动服务器

    ```python
    python manage.py runserver
    ```

完毕。