# django_demo

[django指导文档](https://docs.djangoproject.com/zh-hans/2.0/)

### django 命令集

- python manage.py shell  打开 Python 命令行
- python manage.py test polls 运行测试
- python -c "import django; print(django.\__path__)” Django 的源文件位置

### 改变模型需要这三步：

- 编辑 models.py 文件，改变模型。
- 运行 python manage.py makemigrations 为模型的改变生成迁移文件。
- 运行 python manage.py migrate 来应用数据库迁移。



