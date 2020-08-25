# yarn

> 包管理器

## 常用命令

* 初始化新项目
    ~~~
    yarn init
    ~~~

* 添加依赖包
    ~~~
    yarn add [package]
    yarn add [package]@[version]
    yarn add [package]@[tag]
    ~~~

* 将依赖项添加到不同依赖项类别
    ~~~
    // devDependencies
    yarn add [package] --dev
    // peerDependencies
    yarn add [package] --peer
    // optionalDependencies
    yarn add [package] --optional
    ~~~

* 升级依赖包
    ~~~
    yarn upgrade [package]
    yarn upgrade [package]@[version]
    yarn upgrade [package]@[tag]
    ~~~

* 移除依赖包
    ~~~
    yarn remove [package]
    ~~~

* 安装项目的全部依赖（package.json）
    ~~~
    yarn
    
    // or
    yarn install
    ~~~

* 用户自定义脚本
    ~~~
    yarn <script> [<args>]
    
    // 包脚本（在 package.json 的 script））
    yarn run <script> [<args>]
    ~~~

