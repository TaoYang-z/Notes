ssh设置免密登录
    ssh-keygen -t rsa
    
    scp .ssh/id_rsa.pub xx@192.168.0.2:~/.ssh/authorized_keys