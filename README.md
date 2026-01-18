# 🍅 精英番茄钟 Pro

一个精美的番茄工作法计时器，采用现代化设计，帮助你提高工作效率和专注力。

[English](#english) | [中文](#中文)

---

## 中文

### ✨ 特性

- **🎯 三种工作模式**
  - 专注模式（默认 25 分钟）
  - 短休息（默认 5 分钟）
  - 长休息（默认 15 分钟）

- **🎨 精美的视觉设计**
  - 玻璃态质感界面
  - 流畅的渐变背景动画
  - 圆形进度条实时显示
  - 响应式布局，支持各种屏幕尺寸

- **📊 统计追踪**
  - 已完成番茄数统计
  - 总专注时间记录
  - 数据本地持久化保存

- **🔔 智能提醒**
  - 计时完成时的音效提示
  - 浏览器桌面通知（需授权）
  - 智能推荐下一个模式（每 4 个番茄后建议长休息）

- **⚙️ 自定义设置**
  - 可自由调整各模式时长
  - 设置数据自动保存
  - 支持 1-99 分钟工作时长，1-60 分钟休息时长

- **⌨️ 键盘快捷键**
  - `空格键` - 开始/暂停计时
  - `Enter` - 保存设置（设置界面中）
  - `Esc` - 关闭设置（设置界面中）

- **🔄 后台运行支持**
  - 切换标签页后继续计时
  - 返回时自动同步时间
  - 标签页标题显示剩余时间

### 🚀 快速开始

#### 在线使用

访问 https://zhuxii-sys.github.io/pomodoro_timer/ 直接使用

#### 本地使用

1. 下载 `index.html` 文件
2. 双击文件在浏览器中打开
3. 开始使用！

或者克隆整个仓库：

```bash
git clone https://github.com/your-username/pomodoro-timer.git
cd pomodoro-timer
# 在浏览器中打开 index.html
```

### 📖 使用说明

1. **开始专注**
   - 点击"开始专注"按钮或按空格键
   - 专注工作直到计时结束

2. **模式切换**
   - 点击顶部的模式标签切换工作/休息模式
   - 或在提醒通知中选择推荐的模式

3. **自定义时长**
   - 点击"⚙️"按钮打开设置
   - 调整各模式的时长（分钟）
   - 点击"保存"应用更改

4. **查看统计**
   - 底部显示已完成的番茄数和总专注时间
   - 数据自动保存在浏览器本地存储中

### 🎯 番茄工作法建议

- 每个番茄时间为 25 分钟专注工作
- 完成 1 个番茄后，休息 5 分钟
- 完成 4 个番茄后，休息 15-30 分钟
- 在番茄时间内专注于单一任务
- 避免在番茄时间内被打断

### 🛠️ 技术栈

- 纯 HTML/CSS/JavaScript
- 不依赖任何外部库或框架
- 使用 Web Audio API 生成提示音
- 使用 localStorage 存储数据
- 使用 Notification API 发送桌面通知

### 🌐 浏览器兼容性

- ✅ Chrome/Edge 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Opera 76+

推荐使用最新版本的现代浏览器以获得最佳体验。

### 📱 移动端支持

完全支持移动设备，包括：
- 触摸操作
- 响应式布局
- 移动浏览器通知

### 🔒 隐私说明

- 所有数据仅保存在您的浏览器本地存储中
- 不收集、不上传任何个人信息
- 完全离线可用（下载后）

### 🤝 贡献

欢迎提交 Issue 和 Pull Request！

1. Fork 本仓库
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个 Pull Request

### 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

### 🙏 致谢

- 番茄工作法由 Francesco Cirillo 于 1980 年代末期发明
- 图标 Emoji 来自系统默认字体

---

## English

### ✨ Features

- **🎯 Three Working Modes**
  - Focus Mode (default 25 minutes)
  - Short Break (default 5 minutes)
  - Long Break (default 15 minutes)

- **🎨 Beautiful Visual Design**
  - Glassmorphism UI
  - Smooth gradient background animations
  - Real-time circular progress indicator
  - Responsive layout for all screen sizes

- **📊 Statistics Tracking**
  - Completed pomodoros counter
  - Total focus time tracking
  - Local data persistence

- **🔔 Smart Notifications**
  - Audio alerts on completion
  - Browser desktop notifications (with permission)
  - Smart recommendations (suggests long break after 4 pomodoros)

- **⚙️ Customizable Settings**
  - Adjust duration for each mode
  - Auto-save settings
  - 1-99 minutes for work, 1-60 minutes for breaks

- **⌨️ Keyboard Shortcuts**
  - `Space` - Start/Pause timer
  - `Enter` - Save settings (in settings modal)
  - `Esc` - Close settings (in settings modal)

- **🔄 Background Support**
  - Continues timing when tab is inactive
  - Auto-syncs time when returning
  - Tab title shows remaining time

### 🚀 Quick Start

#### Online Use

Visit https://zhuxii-sys.github.io/pomodoro_timer/ to use directly 

#### Local Use

1. Download the `index.html` file
2. Double-click to open in your browser
3. Start using!

Or clone the repository:

```bash
git clone https://github.com/your-username/pomodoro-timer.git
cd pomodoro-timer
# Open index.html in your browser
```

### 📖 How to Use

1. **Start Focusing**
   - Click "Start Focus" button or press Space
   - Work until the timer completes

2. **Switch Modes**
   - Click mode tabs at the top
   - Or choose recommended mode from notifications

3. **Customize Duration**
   - Click "⚙️" button to open settings
   - Adjust duration for each mode (in minutes)
   - Click "Save" to apply changes

4. **View Statistics**
   - Bottom section shows completed pomodoros and total focus time
   - Data automatically saved in browser local storage

### 🎯 Pomodoro Technique Tips

- Each pomodoro is 25 minutes of focused work
- After 1 pomodoro, take a 5-minute break
- After 4 pomodoros, take a 15-30 minute break
- Focus on a single task during each pomodoro
- Avoid interruptions during pomodoro time

### 🛠️ Tech Stack

- Pure HTML/CSS/JavaScript
- No external libraries or frameworks
- Web Audio API for sound alerts
- localStorage for data persistence
- Notification API for desktop notifications

### 🌐 Browser Compatibility

- ✅ Chrome/Edge 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Opera 76+

Recommended to use the latest version of modern browsers for the best experience.

### 📱 Mobile Support

Fully supports mobile devices including:
- Touch operations
- Responsive layout
- Mobile browser notifications

### 🔒 Privacy

- All data is stored only in your browser's local storage
- No data collection or uploading
- Works completely offline (after download)

### 🤝 Contributing

Issues and Pull Requests are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

### 🙏 Acknowledgments

- The Pomodoro Technique was invented by Francesco Cirillo in the late 1980s
- Emoji icons from system default fonts

---

## 📸 Screenshots

![Work Mode](screenshots/work-mode.png)
![Break Mode](screenshots/break-mode.png)
![Settings](screenshots/settings.png)

> Note: Add actual screenshots to the `screenshots/` folder

---

## 🐛 Known Issues

None at the moment. Please report any bugs in the [Issues](issues) section.

## 🗺️ Roadmap

- [ ] Add sound customization options
- [ ] Add dark/light theme toggle
- [ ] Add task list integration
- [ ] Add daily/weekly statistics charts
- [ ] Add export statistics feature

---

**Made with ❤️ for better productivity**
