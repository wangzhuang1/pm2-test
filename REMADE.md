简单的pm2配置

#pm2
- 进程守护，系统崩溃自动重启
- 启动多进程，充分利用cpu和内存
- 自带日志记录功能
- nodemon是前台运行的，pm2是后台运行的

####下载
```
sudo npm i pm2 -g // 全局安装
pm2 --version // 查看版本
```

####常用命令
```
pm2 start ... // 启动
pm2 list // 查看进程列表
pm2 restart name/id // 手动重启
pm2 stop name/id
pm2 delete name/id
pm2 info name/id // 查看基本信息
pm2 log name/id // 查看日志
pm2 monit name/id // 查看cpu 内存信息
```
