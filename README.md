# 恒发印刷机械企业网站

## 网站结构

```
hengfa-website/
├── index.html          # 首页
├── heat-transfer.html  # 热转印机产品页
├── hot-stamping.html   # 烫金机产品页
├── about.html          # 联系我们/关于我们
├── css/
│   └── style.css       # 样式文件
├── js/
│   └── main.js         # 交互脚本
└── README.md           # 说明文件
```

## 功能特点

- ✅ 响应式设计（适配手机、平板、电脑）
- ✅ 产品分类展示（热转印机、烫金机）
- ✅ 详细产品参数表格
- ✅ 联系方式展示
- ✅ 平滑滚动和动画效果
- ✅ 现代化工业风格设计

## 部署到 GitHub Pages

### 方法一：手动上传（推荐，最安全）

1. 在 GitHub 创建新仓库（如 `hengfa-website`）
2. 将本文件夹内所有文件上传到仓库
3. 进入仓库 Settings → Pages
4. Source 选择 "Deploy from a branch"
5. Branch 选择 "main"，文件夹选择 "/ (root)"
6. 点击 Save，等待几分钟即可访问

访问地址：`https://你的用户名.github.io/hengfa-website/`

### 方法二：使用 Git 命令行

```bash
# 进入网站文件夹
cd hengfa-website

# 初始化 Git 仓库
git init

# 添加所有文件
git add .

# 提交
git commit -m "Initial commit"

# 添加远程仓库（替换为你的仓库地址）
git remote add origin https://github.com/你的用户名/hengfa-website.git

# 推送
git push -u origin main
```

### 方法三：临时 Token 授权部署

如果需要我直接部署：
1. 创建仓库后，生成 Fine-grained Token（仅 Contents 读写权限）
2. 通过安全渠道给我 Token
3. 我部署完成后立即删除 Token

## 自定义域名（可选）

1. 在仓库根目录创建 `CNAME` 文件
2. 文件中写入你的域名（如 `www.hengfa.com`）
3. 在域名 DNS 设置中添加 CNAME 记录指向 `用户名.github.io`
4. 等待 DNS 生效

## 修改内容

- 公司信息：编辑各 HTML 文件中的文本
- 联系方式：在 `about.html` 和 `index.html` 中修改邮箱
- 产品信息：编辑 `heat-transfer.html` 和 `hot-stamping.html`
- 样式：修改 `css/style.css`

## 技术栈

- HTML5
- CSS3（响应式布局）
- JavaScript（原生）
- 无需后端，纯静态网站

## 浏览器兼容

- Chrome / Edge / Firefox / Safari 最新版
- IE11 及以下不支持

---

**生成时间：** 2026年3月5日  
**版本：** v1.0
