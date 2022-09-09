# vue3_yuanma

## vue3(声明式框架)
vue3更注重模块化拆分,vue2无法单独使用某些模块,
vue3耦合度低,可以独立使用某些模块
vue2很多方法挂载在实例上,未使用也会被打包;vue3通过构建工具tree-shaking机制实现按需引入,减小打包体积
vue3允许自定义渲染器,扩展能力强

## pnpm-workspace.yarl
1.monorepo模式管理代码,一个项目仓库管理多个模块/包

## .npmrc
shamefully-hoist = true
修饰提升
尽量少用,pnpm解决了幽灵依赖
