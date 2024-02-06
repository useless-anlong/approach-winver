# Lighter Clock
一个十分朴素的桌面时钟，除了（自认为的）好看。
使用 Electron 构建。

## 开始使用
1. 安装 Electron
```shell
yarn add electron
```
> 不推荐在不换源的情况下在国内使用 npm 安装，因为这将会非常缓慢。
> 使用 yarn -v (Windows) 或 yarn --version 验证 yarn 安装。

2. 调试项目以确保它可以运行
```shell
yarn start
```
> 本项目是在 Electron 23 上开发的远古级项目，您应该执行这步来确保它可以在更新的 Electron 版本上运行。
>
3. 安装 Electron Forge
```shell
yarn add electron-forge
```
4. 打包项目
```shell
electron-forge make
```

此项目已完全停止开发，如发现问题请自己完善。