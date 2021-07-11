
## 13 The Autofac DI Container
- With Autofac, resolving from the root container directly is a bad practice. This can easily lead to memory leaks or concurrency bugs. Instead, you should always resolve from a lifetime scope
- 