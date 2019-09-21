# 使用Verdaccio搭建npm私服

## 安装`verdaccio`

```bash
$> yarn add verdaccio 
```

## 启动`verdaccio`

```bash
$> verdaccio --listen 4000 --config ~./config.yaml
```
-- listen    设置端口号，可省略默认使用配置文件设置的端口号

--config     设置读取配置文件的路径，可省略默认读取用户目录下的配置文件

