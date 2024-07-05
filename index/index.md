# 面对面文件传输

1. [使用python的方式](https://blog.csdn.net/xuq09/article/details/84936853) 

   安装:

   ```python
   pip install pyftpdlib
   ```

   一键开启:

   ```python
   python -m pyftpdlib
   ```

   至此一个简单的FTP服务器已经搭建完成，访问 ftp://127.0.0.1:2121 即可

   （默认IP为 127.0.0.1 、端口为 2121 ）

    

   可选参数
   -i 指定IP地址（默认为本机的IP地址）
   -p 指定端口（默认为2121）
   -w 写权限（默认为只读）
   -d 指定目录 （默认为当前目录）
   -u 指定用户名登录
   -P 设置登录密码



