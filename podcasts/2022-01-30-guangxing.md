# 录制大纲

# 嘉宾个人简介
  - 知乎: https://www.zhihu.com/people/huang-guang-xing-18
  - Github: https://github.com/doyoubi
  - 深圳大学毕业。刚毕业在上海饿了么，现在在新加坡某互联网公司。

# Rust 初印象

## 为什么入坑，用时多久才算有些心得

- 2015年11月用Rust做毕设开始入坑: https://github.com/doyoubi/Blastoise
- 工作后2018年重新捡起，并开始用Rust做开源项目: https://github.com/doyoubi/undermoon

体验了三个阶段:
- Borrow Checker 难用.
- Borrow Checker 得到优化. 基于 combinator 的 Future 可用但难用.
- async/await 稳定.

## 与其他编程语言的区别

- 安全
  - Drop + Future
- 性能
  - 类型系统

曾分别用C, Golang, Rust实现过Redis Proxy.
- C: https://github.com/eleme/corvus
- Golang: https://github.com/samaritan-proxy/samaritan
- Rust: https://github.com/doyoubi/undermoon

# 深入浅出 Rust

## 学习 Rust 有哪些常见的“坑”

- 对象设计
  - self,&self,&mut self
  - 避免大对象
- 依赖注入 与 Object Safety

经验:
- Drop很有用
- Future Group

## Rust 未来的发展方向

- GAT
- Dependent Type: https://www.idris-lang.org/
- Effective Rust

## 根据嘉宾自身经验，着重描述一两件有趣、有价值的事情

### 可以是维护开源软件的经历

Redis Cluster方案: https://github.com/doyoubi/undermoon

- Rust使用感受
- 运营

### 可以是如何给开源软件贡献代码

None


### 也可以是自己认为有别于其他人的事迹

在公司落地Rust:
- 实现Redis基础设施
- 招人
- Tech Talk

# 推荐环节，一些示例：

推荐书：A Mind For Numbers

推荐电影：梅艳芳

买过的产品:
- ipad + Apple Pencil
- 翻译笔
