# bubble清单
一个基于gin+gorm开发的练手小项目，通过该项目可初识go web开发该有的姿势。



## 使用指南

### 下载

```
git clone https://github.com/palp1tate/bubble.git
```

### 配置MySQL

1. 在你的数据库中执行以下命令，创建本项目所用的数据库：

```
CREATE DATABASE bubble DEFAULT CHARSET=utf8mb4;
```

2. 在`mysql.go`文件中配置数据库连接信息。

### 编译

```
go build
```

### 执行

```bash
./bubble
```

启动之后，使用浏览器打开<http://127.0.0.1:8080/>即可。

![image](https://github.com/palp1tate/bubble/assets/120303802/153e14ac-08dd-49e3-9d9d-210701c7c9a2)
