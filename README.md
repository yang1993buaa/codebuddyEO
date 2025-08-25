# 个人博客首页

一个简约大气的个人博客首页设计，采用前后端分离架构，当前版本为纯前端实现。

## 特性

- 🎨 简约现代的设计风格
- 📱 完全响应式布局
- ⚡ 流畅的动画效果
- 🔧 前后端分离架构
- 📝 易于扩展和维护

## 技术栈

- HTML5
- CSS3 (Grid, Flexbox, 动画)
- Vanilla JavaScript
- Google Fonts (Inter字体)

## 页面结构

### 导航栏
- 固定顶部导航
- 响应式汉堡菜单
- 平滑滚动锚点

### 主要区域
1. **英雄区域** - 欢迎标题和CTA按钮
2. **关于区域** - 个人介绍
3. **文章区域** - 最新文章展示
4. **联系区域** - 联系方式

## 设计特点

### 视觉设计
- 使用渐变背景和卡片阴影
- 统一的配色方案
- 优雅的字体排版
- 微交互动画

### 用户体验
- 平滑滚动
- 悬停效果
- 加载动画
- 键盘导航支持

## 快速开始

1. 克隆或下载项目文件
2. 在浏览器中打开 `index.html`
3. 开始自定义内容

## 自定义指南

### 修改内容
- 编辑 `index.html` 中的文本内容
- 替换占位符图片
- 更新联系信息

### 样式调整
- 在 `styles.css` 中修改颜色变量
- 调整字体大小和间距
- 自定义动画效果

### 功能扩展
- 在 `script.js` 中添加新的交互功能
- 集成第三方库
- 添加数据获取逻辑

## 后端集成准备

当前设计已为后端集成做好准备：

### API端点规划
```javascript
// 文章数据
GET /api/articles
GET /api/articles/:id

// 个人信息
GET /api/profile

// 联系表单
POST /api/contact
```

### 数据结构
```javascript
// 文章对象
{
  id: string,
  title: string,
  excerpt: string,
  content: string,
  date: string,
  image: string
}
```

## 浏览器支持

- Chrome (推荐)
- Firefox
- Safari
- Edge

## 性能优化

- CSS Grid 和 Flexbox 布局
- 防抖滚动事件
- 图片懒加载准备
- 代码分割准备

## 部署建议

### 静态托管
- Netlify
- Vercel
- GitHub Pages

### CDN优化
- 图片压缩
- 资源缓存
- Gzip压缩

## 后续开发计划

1. **第二阶段：后端集成**
   - Node.js + Express 或其他后端框架
   - 数据库集成 (MongoDB/PostgreSQL)
   - RESTful API 开发

2. **第三阶段：功能增强**
   - 文章搜索功能
   - 标签分类系统
   - 评论系统
   - 管理后台

3. **第四阶段：高级特性**
   - PWA 支持
   - 深色模式
   - 多语言支持
   - SEO 优化

## 许可证

MIT License

## 贡献

欢迎提交 Issue 和 Pull Request！