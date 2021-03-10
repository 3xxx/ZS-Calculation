# 常用计算模块
## 使用环境

ANSYS宏文件是以.mac为后缀的文件，又称命令流文件。可在经典模式下使用，能够简化操作提高计算效率。

推荐使用ANSYS19或19.1版本，最低不能低于18，也**不能使用更高版本**，最新的版本中对link10单元不再支持，会影响某些宏命令。

Python自动化计算代码是以.py为后缀的文件，需下载到电脑，且安装相关的执行软件方能运行。

* [Python3.8.8 下载](https://www.python.org/ftp/python/3.8.8/python-3.8.8-amd64.exe)
* [**局域网下载Python**](https://xuming.science/file/python.rar)

推荐**安装使用Visual Studio Code**代码编辑软件：

* [Visual Studio Code](https://code.visualstudio.com/)
* [**局域网下载VScode**](https://xuming.science/file/VS.rar)

**Python修改pip源地址**

1. 下载所需文件[pip.ini](docs/pip.ini)
2. 打开C盘当前用户的文件夹，例如`C:\Users\Administrator`
3. 在用户目录下新建名为`pip`的文件夹
4. 将第一步下载的文件移动到第三步新建的文件夹内，最终该文件的路径如前例所示为`C:\Users\Administrator\pip\pip.ini`

### 常用python模块安装

python代码通常会调用一些第三方模块，需要提前安装才能正常运行代码。

安装方法如下：

1. 按<kbd>Win</kbd> + <kbd>R</kbd> 调出运行窗口，输入cmd，点击确定，调出命令控制行

![cmd](images/cmd.png)

2. 逐行复制粘贴以下代码到命令控制行，粘贴一行按下回车，逐行操作
```
pip install python-docx
pip install pandas
pip install Pillow
pip install matplotlib
```
![cmd2](images/cmd2.png)

## 埋件计算


## 外挂架计算



## 内爬钢梁计算

## 附着计算

## 压杆稳定校核

## 在线计算小工具

*（仅适用于公司内部网络）*

* [行走轮压计算](http://192.168.16.198/lunya.php)
* [动臂吊臂头部侧向等效载荷计算](http://192.168.16.198/pianbai.php)
* [塔机固定基础稳定及所需地耐力估算](http://192.168.16.198/jichu.php)

## ANSYS常用技术

[ANSYS画弯矩图、剪力图、轴力图](ANSYS画弯矩图、剪力图、轴力图.md)

[ANSYS经典模式自定义工具栏](ANSYS经典模式自定义工具栏.md)

