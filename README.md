Python Implementation of Apriori Algorithm 
==========================================

开发环境
-----

1. 下载python3，并在对应的系统中进行安装[python下载](https://www.python.org/downloads/)

2. 安装对应的依赖

```sh
# pip3 对应 python3
pip3 install -r requirements.txt
```

命令行使用
-----

1. 命令行启动

```python
# 默认启动
python3 apriori.py -f test.xlsx

# 带参数启动
python3 apriori.py -f test.xlsx -s 0.1 -c 0.6 -p 3
```

参数说明：
- -f <excel文件名>，excel文件所在的目录
- -s <value>, minSupport，最小支持度，默认为0.1
- -c <value>, minConfidence，最小信任度，默认为0.6
- -p <value>, startDataPosition，运算数据在excel表格中的位置，默认为3

