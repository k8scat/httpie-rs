# httpie-rs

Rust 实现简易版的 [httpie](https://github.com/httpie/httpie)。

```bash
# 下载
git clone https://github.com/k8scat/httpie-rs.git
cd httpie-rs

# 构建
cargo build

# get 请求
./target/debug/httpie-rs get https://httpbin.org/get

# post 请求
./target/debug/httpie-rs post https://httpbin.org/post a=1 b=2

# 单元测试
cargo test
```
