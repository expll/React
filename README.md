
# 启动React项目
```
npm start
```


#  部署服务器后路由失效问题
解决办法：
配置nginx:
```
location / {
    try_files $uri /index.html;
}
```
