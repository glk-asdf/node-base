# npm

## npm 请求超时

> 是因为网络问题，可改用 taobao 

1. 使用 --registry

    ~~~
    npm install --registry=https://registry.npm.taobao.org
    ~~~

2. 使用 cnpm

    > cnpm 不像 npm（检查文件完整性），只要有下载（不管是否下载完全），就会跳过，以效率为主

    ~~~
    npm install -g cnpm --registry=https://registry.npm.taobao.org
    ~~~

3. 修改 npm 的 config registry

    ~~~
    // set taobao
    npm config set registry https://registry.npm.taobao.org
    // get
    npm config get
    // reduction
    npm config set registry http://registry.npmjs.org
    ~~~

    * 在 C:\Users\DEV4\.npmrc 中记录着设置的 config		( .rc  Resource compilation 资源编译器)


## npm 常用命令

> 使用 npm 的项目，不适合放在系统盘，经常会有权限问题

### 查看包版本

~~~
npm view xxx version
~~~
