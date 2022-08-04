# sync

## errgroup

与 golang.org/x/sync/errgroup 操作界面和实现逻辑一样，针对性进行以下改进：

- 对 Go / TryGo 的参数 f 进行包装，recover 它的 panic
