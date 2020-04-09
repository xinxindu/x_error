# x_error
## 递归显示error调用信息
```go 
// 创建一个msg的error
ErrorMsg(msg string) error

// 创建一个err的error
Error(err error) error

// 创建一个给err额外追加msg的error
ErrorWithMsg(err error, msg string) error
```


