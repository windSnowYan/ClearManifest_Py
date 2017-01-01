# ClearManifest_Py
去除AndroidManifest.xml里重复申请的权限（uses-permission）

使用说明：

本程序使用ElementTree对XML进行处理，它在Python2.5以后成为Python标准库的一部分，但是Python2.4之前需要单独安装。

使用方法：

将 ClearManifest.py 和 AndroidManifest.xml 放在一个文件夹下

然后执行 python ClearManifest.py

得到的 AndroidManifest.xml 就是清理后的文件（ AndroidManifest_backup.xml 为备份）
