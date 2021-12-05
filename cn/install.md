## 服务器要求

- Golang >= 1.11

## 安装 Goravel

```shell
git clone git@github.com:goravel/goravel.git 
cd goravel && go mod tidy
cp .env.example .env
```

## 启动 HTTP 服务

`go run .`

框架内置 [cosmtrek/air](https://github.com/cosmtrek/air) 配置文件，可直接使用

`air`