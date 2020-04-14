## 環境構築

* golang install
    - https://qiita.com/yut-kt/items/9f5ac1e788df61f64290

* go get(go modulesはまだ未対応)

```
go get -u google.golang.org/grpc
go get -u github.com/golang/protobuf/protoc-gen-go
cd ~/go/1.14.2/src/github.com/golang/protobuf/protoc-gen-go
go build
mv protoc-gen-go ~/go/1.14.2/bin
```

## 実行

```
go run 


## 参考URL

* https://qiita.com/marnie_ms4/items/4582a1a0db363fe246f3


