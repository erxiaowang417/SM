
### 使用说明
#### 1.下载与安装
- [官网链接](https://www.openssl.org/source/) - 
- 安装 ``` cd XXX //进入压缩包所在目录 tar xzvf openssl-1.0.2t.tar.gz //解压 
- cd openssl-1.0.2t //进入安装目录 ./config //拷贝相关文件 
- make //编译 make install //安装 需要权限 ``` 
- 确认文件 ``` cd usr/include/openssl ls ``` ![](https://img2018.cnblogs.com/blog/1268742/201911/1268742-20191118195127572-884913548.png)
- cd usr/lib/ssl
- ls
#### 2.简单说明
- openssl: 多用途的命令行工具，可以执行交互或批量命令。 
- -注：请在终端使用```man openssl```和```openssl --help```命令了解其相关信息 - libcrypto: 加密算法库。 - libssl：加密模块应用库，实现了ssl及tls。

