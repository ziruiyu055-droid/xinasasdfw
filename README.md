# 精神类药物网页部署指南

## 文件夹结构

```
website/
├── index.html    # 主页面
├── drug1.png     # 利他能图片
├── drug2.png     # 择思达图片
├── drug3.png     # 专注达图片
└── drug4.png     # 左洛复图片
```

## 部署到 Gitee Pages（推荐，国内访问快）

### 步骤 1: 注册/登录码云

1. 访问 https://gitee.com 注册账号（推荐使用手机号注册）
2. 登录后点击右上角 "+" → "新建仓库"

### 步骤 2: 创建仓库

1. 仓库名称填写：`psychotropic-medications`（或其他英文名）
2. 选择"公开"仓库
3. 勾选"使用README文件初始化仓库"
4. 点击"创建"

### 步骤 3: 上传网页文件

1. 进入仓库页面
2. 点击 "上传" 按钮
3. 将 `website` 文件夹内的所有文件拖拽上传：
   - index.html
   - drug1.png
   - drug2.png
   - drug3.png
   - drug4.png
4. 填写提交信息，点击"提交"

### 步骤 4: 开启 Gitee Pages

1. 在仓库页面左侧菜单点击"服务" → "Gitee Pages"
2. 选择分支（master/main）
3. 点击"部署"
4. 等待几秒钟，你会获得一个网址，例如：
   `https://你的用户名.gitee.io/psychotropic-medications/`

### 步骤 5: 自定义域名（可选）

如果你有自己的域名，可以在 Gitee Pages 设置中添加自定义域名。

---

## 部署到 GitHub Pages（备选方案）

如果你有梯子，也可以使用 GitHub Pages：

1. 在 GitHub 创建新仓库
2. 上传所有文件
3. Settings → Pages → 选择 branch 和目录
4. 访问 `https://你的用户名.github.io/仓库名/`

---

## 常见问题

### Q: Gitee Pages 访问慢？
A: Gitee 在国内访问速度很快。如果仍然慢，可以考虑购买 Gitee Pro（每月9元）获得独立加速。

### Q: 页面显示404？
A: 确保文件名是 `index.html`，且在 Gitee Pages 设置中正确选择了分支。

### Q: 图片无法显示？
A: 检查图片文件名是否完全一致（大小写敏感）。确保图片在仓库根目录。

---

## 更新网页

修改本地文件后，只需重新上传覆盖即可，Gitee Pages 会自动更新。
