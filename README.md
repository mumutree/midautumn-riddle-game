# 中秋猜谜语游戏 🎑

一个基于Web的中秋节猜谜语游戏，具有响应式设计和友好的用户界面。

## 功能特点

- 🎯 丰富的谜语库
- 📱 响应式设计，支持手机、平板和电脑
- 🎨 精美的中秋主题UI
- ✅ 智能答案验证（支持部分匹配和同义词）
- 🏆 积分系统
- 🔍 显示答案功能

## 快速开始

### 1. 克隆项目
```bash
git clone https://github.com/your-username/mid-autumn-riddle-game.git
cd mid-autumn-riddle-game
```

### 2. 配置Supabase
1. 复制配置文件模板：
```bash
cp config.example.js config.js
```

2. 在 `config.js` 中填入您的Supabase配置：
```javascript
const SUPABASE_CONFIG = {
    URL: 'https://your-project.supabase.co',
    ANON_KEY: 'your-anon-key-here'
};
```

### 3. 启动游戏
直接在浏览器中打开 `index.html` 文件，或使用本地服务器：
```bash
# 使用Python
python -m http.server 8000

# 使用Node.js (需要先安装 http-server)
npm install -g http-server
http-server -p 8000
```

然后在浏览器中访问 `http://localhost:8000`

## 游戏玩法

1. **登录/注册**：输入用户名和密码
2. **猜谜语**：阅读显示的谜语，在输入框中输入答案
3. **验证答案**：点击提交或按Enter键验证答案
4. **获得积分**：答对谜语获得10分，使用"显示答案"功能获得5分
5. **跳过谜语**：如果遇到难题，可以跳过当前谜语

## 技术栈

- **前端**：HTML5, CSS3, JavaScript (ES6+)
- **数据库**：Supabase (PostgreSQL)
- **部署**：GitHub Pages (可选)

## 浏览器支持

- ✅ Chrome (推荐)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ 移动端浏览器

## 项目结构

```
mid-autumn-riddle-game/
├── index.html          # 主页面
├── config.js           # Supabase配置文件（需要自行配置）
├── config.example.js   # 配置文件示例
├── riddles.js          # 谜语数据库
├── .gitignore          # Git忽略文件
└── README.md           # 项目说明
```

## 贡献

欢迎提交Issue和Pull Request来改进这个游戏！

## 许可证

MIT License

## 联系方式

如有问题，请通过GitHub Issues联系我们。

---

🎉 祝您中秋快乐，玩得开心！