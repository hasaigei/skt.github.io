### docker学习记录

# dicker安装
    docker安装在linux上，因为windows不常用此处不做介绍
    # 1，用yum安装docker
    yum list docker-ce --showduplicates | sort -r
    
    $ sudo yum install docker-ce  #由于repo中默认只开启stable仓库，故这里安装的是最新稳定版17.12.0
    $ sudo yum install <FQPN>  # 例如：sudo yum install docker-ce-17.12.0.ce
    
    # 设置开机启动
    $ sudo systemctl start docker
    $ sudo systemctl enable docker
    
    # 验证是否安装成功
    
    $ docker version
