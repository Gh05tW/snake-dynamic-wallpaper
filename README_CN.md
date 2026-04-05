🇨🇳 中文文档 | [English](README.md)
# 贪吃蛇动态壁纸

一个贪吃蛇游戏动画，作为 Windows 桌面壁纸。

![](https://cdn.jsdelivr.net/gh/Gh05tW/snake-dynamic-wallpaper@main/images/example.png)

## 功能特点

- **AI 寻路**：贪吃蛇使用贪心算法主动寻找食物
- **碰撞躲避**：自动躲避自身和屏幕边界
- **平滑渲染**：转角圆滑处理，移动更自然
- **连续蛇身**：路径上蛇身无缝连接

## 系统要求

- **显示器**：1920x1080 分辨率
- **操作系统**：Windows 10/11
- **软件**：[Lively Wallpaper](https://www.microsoft.com/store/productId/9NTM2QC6QWS7)

## 安装

1. 从 Microsoft Store 安装 [Lively Wallpaper](https://www.microsoft.com/store/productId/9NTM2QC6QWS7)
2. 将 `lively/index.html` 拖入 Lively Wallpaper 窗口
3. 完成

## 自定义

编辑 `lively/index.html`：

```javascript
const CELL_SIZE = 15;      // 方块大小 (像素)
const GAP_SIZE = 5;        // 网格间隔 (像素)
const INITIAL_LENGTH = 5;  // 蛇的初始长度
const GROW_AMOUNT = 15;    // 吃食物后增长量
const FRAME_DELAY = 30;    // 速度 (毫秒，越小越快)
```

## 文件结构

```
dynamic-wallpaper/
├── lively/
│   └── index.html         # 壁纸文件
├── images/
│   └── example.png        # 截图
└── README.md
```

## 许可证

MIT
