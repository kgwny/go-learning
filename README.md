# go-learning

## go.mod の初期化
```
go mod init github.com/username/go-learning
```

## go get により echo をインストール
```
go get -u github.com/labstack/echo
```

## echo によるWebサーバの起動
```
go run main.go
```

```
   ____    __
  / __/___/ /  ___
 / _// __/ _ \/ _ \
/___/\__/_//_/\___/ v3.3.10-dev
High performance, minimalist Go web framework
https://echo.labstack.com
____________________________________O/_______
                                    O\
⇨ http server started on [::]:8080
```

`http://localhost:8080` にアクセスする　　

`Hello world!` が画面表示されたら確認OK
