# sourcemap-stacktrack-parser

## 网站链接

[](https://juejin.cn/post/6844904063457312781)
## 依赖

yarn add -D typescript ts-node-dev @types/node

创建 tsconfig.json

### ts-node-dev

[分享快速搭建 Node 端 TypeScript 开发环境](https://juejin.cn/post/6844904052816347149)

```json
{
  "scripts": {
    "start": "tsnd -P ./tsconfig.json --respawn ./main.ts"
  }
}
// tsnd 是  ts-node-dev 的缩写 , 所以也可以写全  --respawn 即为观察文件变更以重新运行脚本
```

### @types/node

提供node类型声明包,对node 提供api方法有默认提示和检查

### 安装jest库

yarn add -D jest ts-jest @type/jest

配置jest 配置文件

[configuring jest](https://jestjs.io/zh-Hans/docs/configuration)

依赖环境 有两种 (因为该工程用的是 ts的搭建的ts 而不是 babel搭建的)

[jest初始化 && typescript && babel && ts-jest](https://juejin.cn/post/6844903879759364110)

ts-jest 和 babel-jest , 所以要在配置文件中进行指定`transform`

## 安装eslint

yarn add  -D prettier tslint tslint-config-prettier

### 配置tslint.json

### 配置.prettierrc

格式化代码工具。用来保持团队的项目风格统一

### 配置.editorconfig

## 安装git校验钩子

yarn add -D husky
