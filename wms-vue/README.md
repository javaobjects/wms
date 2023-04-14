
<p align="center"><a href='https://docs.oracle.com/en/java/javase/8'><img alt="Java 8" src="
https://img.shields.io/badge/Java%208-%234479A1.svg?logo=data:image/png"
</a>
    <a href='https://docs.spring.io/spring-boot/docs/2.0.0-SNAPSHOT/reference/html'>
<img alt="Spring Boot 2" src="https://img.shields.io/badge/Spring%20Boot%202-%23000000.svg?logo=springboot">
</a>
    <a href='https://staging-cn.vuejs.org'>
<img alt="Vue 3" src="https://img.shields.io/badge/Vue%202%20-%232b3847.svg?logo=vue.js">
</a><br/>
    <a href='https://github.com/201206030/novel'><img alt="Github stars" src="https://img.shields.io/github/stars/201206030/novel?logo=github"></a>
    <a href='https://github.com/201206030/novel'><img alt="Github forks" src="https://img.shields.io/github/forks/201206030/novel?logo=github"></a>
    <a href='https://gitee.com/novel_dev_team/novel'><img alt="Gitee stars" src="https://gitee.com/novel_dev_team/novel/badge/star.svg?theme=gitee"></a>
    <a href='https://gitee.com/novel_dev_team/novel'><img alt="Gitee forks" src="https://gitee.com/novel_dev_team/novel/badge/fork.svg?theme=gitee"></a>
</p>

# 仓库管理系统-客户端

#### 介绍
vue 2.6.11 仓库管理系统
#### 配置环境
1. Nvm1.1.10
2. Node 8.12.0
#### 开发工具
1. IntelliJ IDEA 2022.3.2
2. Git 2.24.1
#### 开发环境
Windows
#### 安装教程
+ 你可以在package.json的父目录执行下如命令 或者 直接在IDEA里点击也可运行 值得一提的是后两命令分别是打包命令和检查修复命令
```
npm install
```
```
npm run serve
```
```
npm run build
```
```
npm run lint
```

#### 编码规范

- 规范方式：严格遵守阿里编码规约。
- 命名统一：简介最大程度上达到了见名知意。
- 分包明确：层级分明可快速定位到代码位置。
- 注释完整：描述性高大量减少了开发人员的代码阅读工作量。
- 工具规范：使用统一jar包避免出现内容冲突。
- 代码整洁：可读性、维护性高。
- 依赖版本：所有依赖均使用当前最新可用版本以便新技术学习。

#### 包的结构

```
    +- public
        +- favicon.ico
        +- index.html
    +- src
        +- assets
        +- components
        +- router
        +- store
        +- App.vue
        +- main.js
    +-  .gitignore
    +-  bable.config.js
    +-  LICENSE
    +-  package.json
    +-  packge-lock.json
    +-  README.md
```
