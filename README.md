# node-base

## npm 跨域问题

### 使用 --registry

~~~
npm install --registry=https://registry.npm.taobao.org
~~~

### 使用 cnpm

~~~
npm install -g cnpm --registry=https://registry.npm.tobao.org
~~~

### 修改 npm 的 config registry

~~~
// set taobao
npm config set registry https://registry.npm.taobao.org
// get
npm config get
// reduction
npm config set registry http://registry.npmjs.org
~~~
