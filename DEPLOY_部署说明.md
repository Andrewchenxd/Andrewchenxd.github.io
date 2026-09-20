# 上线步骤 · Deploy to GitHub Pages

你的主页地址将是：**https://andrewchenxd.github.io**

## 本地文件位置

```
d:\demo\diff差异\Andrewchenxd.github.io\
```

## 部署步骤

### 1. 在 GitHub 上新建仓库

打开：https://github.com/new

- **Repository name** 必须是：`Andrewchenxd.github.io`
- 选择 **Public**
- **不要**勾选 "Add a README file"（本地已有完整模板）
- 点击 **Create repository**

### 2. 推送本地代码

在 PowerShell 中执行：

```powershell
cd "d:\demo\diff差异\Andrewchenxd.github.io"

# 清除模板自带的 origin（如果指向 academicpages）
git remote remove origin 2>$null
git remote add origin https://github.com/Andrewchenxd/Andrewchenxd.github.io.git

# 建议用 main 分支
git branch -M main
git add .
git commit -m "Initial commit: personal academic homepage for Shuai Chen"
git push -u origin main
```

> 如果提示需要登录，可安装 [GitHub CLI](https://cli.github.com/) 后执行 `gh auth login`，
> 或在推送时使用 Personal Access Token（GitHub → Settings → Developer settings → Tokens）。

### 3. 开启 GitHub Pages

1. 打开仓库：https://github.com/Andrewchenxd/Andrewchenxd.github.io
2. **Settings** → 左侧 **Pages**
3. **Build and deployment** → Source 选择 **Deploy from a branch**
4. Branch 选择 **main**，文件夹选 **/ (root)**
5. 点 **Save**

等待 1–3 分钟，访问：

```
https://andrewchenxd.github.io
```

### 4. （可选）本地预览

如果本机装了 Ruby + Bundler：

```powershell
cd "d:\demo\diff差异\Andrewchenxd.github.io"
bundle install
bundle exec jekyll serve
```

浏览器打开 http://localhost:4000

---

## 已填入的信息（来自简历 + Google Scholar）

| 模块 | 文件 | 状态 |
|------|------|------|
| 站点配置（姓名/Scholar/GitHub/邮箱） | `_config.yml` | ✅ |
| 导航菜单（主页/论文/简历） | `_data/navigation.yml` | ✅ |
| 主页 About（中英双语） | `_pages/about.md` | ✅ |
| 简历 CV（中英双语） | `_pages/cv.md` | ✅ |
| 论文列表（12 篇，含引用与要点） | `_publications/*.md` | ✅ |
| 论文页标题 | `_pages/publications.html` | ✅ |

### 已写入的关键事实

- 姓名：陈帅 Shuai Chen
- 邮箱：shuai_chen@stu.xidian.edu.cn
- 电话：15324104859（写在 CV 页，主页可按需去掉）
- 学术：https://scholar.google.com/citations?user=MfHFGkoAAAAJ&hl=zh-CN
- GitHub：Andrewchenxd
- 教育：西电本科 AI（2019.09–2023.06）→ 西电硕士 计算机科学与技术 A-（2023.09–至今）
- 工作：小米小爱算法策略实习 2025.02–2025.09 → **正式工 2026.07 起**（大模型视觉多模态组）
- 项目：GUI 多模态 13 类信息抽取、ScreenR1-SFT / ScreenR1-COT、SFT→RL、ICLR 2026 在投
- 线上指标：打电话 96.27%、导航 95.28%、预识别 95%
- 其他项目：中国电科电磁基础模型、中航工业无人机小目标检测
- 专利：CN114494873
- 荣誉：国家奖学金、校长奖提名、华为奖学金、北斗杯全国一等奖等
- 技能：PyTorch/TF/MindSpore/HF、Python/C++/Matlab、LLM 重编程与微调

---

## 上线后你可以继续改

| 想改什么 | 改哪个文件 |
|----------|------------|
| 头像照片 | 替换 `images/profile.png`（正方形） |
| 邮箱 / 手机 | `_config.yml`、`_pages/about.md`、`_pages/cv.md` |
| 个人简介 | `_pages/about.md` |
| 加/删论文 | `_publications/` 目录下增删 `.md` |
| 顶栏菜单 | `_data/navigation.yml` |
| 挂简历 PDF | 把 PDF 放进 `files/`，访问 `https://andrewchenxd.github.io/files/xxx.pdf` |
| 主题颜色 | `_config.yml` 里 `site_theme`（default / air / sunrise / mint / dirt / contrast） |

### 建议下一步

1. 把 `images/profile.png` 换成你的照片
2. 把简历 PDF 复制到 `files/ChenShuai_CV.pdf`，在 About/CV 页加下载链接
3. 若有论文 PDF，同样放进 `files/`，并把 `_publications/*.md` 里的 `paperurl` 改成对应链接
