# 打砖块游戏 🎮

一个使用HTML5 Canvas制作的经典打砖块游戏，具有现代的视觉效果和流畅的游戏体验。

## 📦 项目结构

```
└── 打砖块.html       # 游戏主文件
└── README.md        # 项目说明文件
```

## 🎨 游戏特色

### 核心玩法
- **鼠标控制**：移动鼠标来控制底部挡板
- **消除砖块**：用小球击碎上方的彩色砖块
- **生命系统**：3条生命，用完游戏结束
- **关卡系统**：清除所有砖块后进入下一关

### 视觉效果
- 炫酷的霓虹渐变背景
- 发光效果的球和挡板
- 带有高光的砖块样式
- 流畅的动画效果

### 游戏机制
- **物理反弹**：挡板不同位置击球会有不同角度
- **难度递增**：每100分球速会加快
- **得分系统**：每消除一块砖 +10分
- **关卡进阶**：每通过一关球速会进一步加快

## 🚀 如何开始

1. **直接打开**：在浏览器中打开 `打砖块.html` 文件
2. **点击开始**：点击游戏画布开始游戏
3. **控制方法**：移动鼠标控制挡板位置

## 📱 技术栈

- **前端技术**：HTML5, CSS3, JavaScript
- **图形绘制**：HTML5 Canvas API
- **动画效果**：requestAnimationFrame
- **响应式设计**：适配不同屏幕尺寸

## 🎯 游戏规则

1. 使用鼠标移动控制底部挡板
2. 小球碰到砖块会反弹并消除砖块
3. 小球碰到挡板会根据碰撞位置产生不同的反弹角度
4. 小球落地会减少一条生命
5. 3条生命用完游戏结束
6. 消除所有砖块后进入下一关
7. 每100分球速会逐渐加快

## 📊 游戏数据

- **画布尺寸**：800px × 500px
- **砖块数量**：5行 × 10列 = 50块
- **初始球速**：5
- **初始生命**：3
- **得分规则**：每块砖 10分

## 🎨 颜色方案

- **背景**：深色渐变（#1a1a2e → #16213e → #0f3460）
- **主色调**：霓虹红（#e94560）
- **砖块颜色**：红、橙、黄、绿、蓝、紫
- **文字颜色**：白色和霓虹红

## 🌟 游戏截图

### 游戏开始界面
![游戏开始界面](https://trae-api-cn.mchost.guru/api/ide/v1/text_to_image?prompt=brick%20breaker%20game%20start%20screen%20with%20dark%20gradient%20background%20and%20neon%20red%20title&image_size=square_hd)

### 游戏中界面
![游戏中界面](https://trae-api-cn.mchost.guru/api/ide/v1/text_to_image?prompt=brick%20breaker%20game%20in%20progress%20with%20colorful%20bricks%20and%20neon%20paddle%20and%20ball&image_size=square_hd)

### 游戏结束界面
![游戏结束界面](https://trae-api-cn.mchost.guru/api/ide/v1/text_to_image?prompt=brick%20breaker%20game%20over%20screen%20with%20final%20score%20display&image_size=square_hd)

## 🤝 贡献

欢迎提交 Issue 和 Pull Request 来改进这个游戏！

## 📄 许可证

本项目采用 MIT 许可证。

## 🌟 感谢

- 感谢 HTML5 Canvas API 提供的绘图能力
- 感谢 JavaScript 提供的交互功能
- 感谢 CSS3 提供的视觉效果

---

**享受游戏！** 🎮✨
