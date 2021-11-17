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