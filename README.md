#### Nginx相关命令
```bash 
sudo nginx #打开 nginx
nginx -s reload|reopen|stop|quit  #重新加载配置|重启|停止|退出 nginx
nginx -t   #测试配置是否有语法错误
```

#### v2ray常用命令
```bash
vi /etc/v2ray/config.json #修改配置文件
sudo systemctl restart v2ray #重启v2ray
service v2ray status #查看v2ray服务状态
```

#### vscode
```
^\s*\n (去除空白行)
```

#### 复制vim的内容到Mac粘贴板
```bash
:%w !pbcopy
```
