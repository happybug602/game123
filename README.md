# 锦鲤追风记 🎮

一个三关小游戏，包含贪吃蛇、铁链桥、怪物追击三个关卡，支持键盘和触屏操作。

## 项目信息

- **GitHub 仓库**: https://github.com/happybug602/game123
- **IGA Pages 项目**: https://console.volcengine.com/dcdn/pages/detail/pcniri7p95

## 游戏介绍

### 第一关：贪吃蛇 🐍
控制紫色小蛇吃掉彩色小球，每吃一个球蛇会变长，同时球会变大。吃掉 10 个球通关。

### 第二关：铁链桥 🌉
穿越铁链桥，躲避飞来的子弹，收集绿色补给恢复生命值。可以跳跃和蹲下躲避不同高度的子弹。

### 第三关：怪物追击 🐻
被狗熊追赶，同时要躲避啄木鸟的攻击，射击消灭啄木鸟。跳过坑洞避免损失生命，到达终点触发彩蛋。

## 操作说明

### 键盘操作
- `↑↓←→`：控制蛇方向/角色移动/瞄准
- `W/↑`：跳跃
- `S`：蹲下（第二关）
- `空格`：射击（第三关）
- `Enter`：开始游戏/继续

### 触屏操作
- 滑动：控制方向/跳跃
- 点击屏幕：开始游戏/交互

## 音频效果

- 背景音乐：程序化生成的活泼快乐旋律
- 吃球音效、跳跃音效、射击音效
- 中弹/受伤音效
- 关卡完成/彩蛋的掌声喝彩

## 部署方式

### 本地运行
直接用浏览器打开 [index.html](file:///d:/workspace/game123/index.html) 即可游玩。

### IGA Pages 部署
```bash
# 登录（使用 Access Key）
iga login --accessKey <AK> --secretKey <SK>

# 部署
iga pages deploy --name game123
```

### GitHub Pages 部署
在仓库 Settings → Pages → Source 选择 `main` 分支即可。

## 技术栈

- HTML5 Canvas
- JavaScript（原生，无框架）
- Web Audio API（音频生成）
- 响应式触屏支持

---
Project ID: pcniri7p95
