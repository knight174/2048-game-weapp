# 2048 小游戏

一个使用 Taro + React 开发的 2048 小游戏,支持多端运行。

## 功能特点

- 经典的 2048 游戏玩法
- 支持触摸滑动和键盘操作
- 记录最高分
- 响应式布局,适配不同屏幕
- 游戏规则说明
- 胜利/失败判定

## 技术栈

- Taro 4.0
- React 18
- TypeScript
- Taro UI
- Sass

## 支持平台

- 微信小程序
- H5
- 支付宝小程序
- 字节跳动小程序
- QQ小程序
- 京东小程序
- 鸿蒙系统

## 本地开发

1. 安装依赖
```bash
npm install
```

2. 启动开发环境
```bash
# 微信小程序
npm run dev:weapp
# H5
npm run dev:h5
```

3. 打包
```bash
# 微信小程序
npm run build:weapp
# H5
npm run build:h5
```
## 项目结构
```
├── src # 源码目录
│ ├── components # 组件
│ ├── constants # 常量定义
│ ├── hooks # 自定义 hooks
│ ├── pages # 页面
│ ├── store # 状态管理
│ ├── utils # 工具函数
│ ├── app.config.ts # 全局配置
│ └── app.ts # 入口文件
├── config # 编译配置
├── types # 类型定义
└── project.config.json # 小程序项目配置
```

## 游戏规则

1. 使用键盘方向键或滑动屏幕来移动方块
2. 相同数字的方块相撞时会合并成为它们的和
3. 每次移动后,会在空白处随机出现一个 2 或 4
4. 当无法移动时游戏结束
5. 当出现 2048 时获得胜利
6. 挑战自己,获得更高分数！

## License

MIT