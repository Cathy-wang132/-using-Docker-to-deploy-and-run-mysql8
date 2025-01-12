# -using-Docker-to-deploy-and-run-mysql8
linux系统使用 docker 来部署运行 mysql8 并配置 docker-compose-mysql.yml 文件
Docker是一个开源的容器化平台，旨在简化应用程序的创建、部署和管理。它基于OS-level虚拟化技术，通过将应用程序和其依赖项打包到一个称为容器的标准化单元中，使得应用程序可以在任何环境中快速、可靠地运行。

#### Docker的优势有以下几个方面：
轻量级和快速：Docker容器与主机共享操作系统内核，因此比传统虚拟化技术更轻量级且启动更快。

可移植性：Docker容器可以在任何支持Docker的主机上运行，无论是物理机、虚拟机还是云服务提供商。

灵活性：Docker容器可以隔离不同的应用程序及其依赖项，因此可以同时运行多个应用程序，而不会相互干扰。

所以 对于服务器部署应用 都使用 docker 来完成部署。下面 我分享自己制作的docker 镜像 和docker-compose-mysql.yml 文件 以后给服务器部署 可以直接使用 方便快捷！

docker 的安装 和 配置 这边就不分享了

直接分享一下 Dockerfile 和 docker-compose-mysql.yml 文件

#### Dockerfile文件
![image](https://github.com/user-attachments/assets/93949bf9-811f-49fd-8f78-ce50b8411b43)

#### docker-compose-mysql.yml 文件
![image](https://github.com/user-attachments/assets/dbe518eb-9c0e-45a2-8960-d560cb95964b)

大家可以按需进行修改

#### 两个文件的获取地址：
https://wwwoop.com/home/Index/projectInfo?goodsId=7&typeParam=3
