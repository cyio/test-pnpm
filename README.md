# pnpm

多项目管理

基于内容寻址的文件系统来存储磁盘上所有的文件

npm/yarn 虽然有下载缓存，但项目安装时还是会再本地拷贝（多次写入）

require: node 14+

> The “p” in pnpm stands for “performant” — and wow, it really does deliver performance!

```
pnpm add shared-ui --filter vite-project --workspace
pnpm add nx -D -w
npx nx dev vite-project

// 递归添加
pnpm add A -r
```
https://blog.nrwl.io/setup-a-monorepo-with-pnpm-workspaces-and-speed-it-up-with-nx-bc5d97258a7e#d69f
