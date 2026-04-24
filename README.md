# Psych-Stats-R-2 · 心理统计R语言教学文档

![R](https://img.shields.io/badge/R-4.0%2B-blue) 
![License](https://img.shields.io/badge/License-MIT-green)


> 一份配合心理统计下的R交互式教学文档，持续更新维护中。之后我有时间会去做心理统计1的文档。
## 📖 项目简介

本教学文档是我在本科期间修读心理统计学课程期间，结合：
- 课程上机代码与询问助教
- 网络上的各类R的参考文档
- 与AI互相拷问互相折磨

最终整理形成的R交互式教学文档。文档按照心理统计学内容进行了分类，**每个核心函数都标注了函数名、参数配置方式、参数的具体含义、对应的统计方法及其作用等内容**。

## 🎯 适用人群

- 正在学习心理统计学、需要使用R进行数据分析的学生
- 希望用R复现心理统计各类分析的初学者
- 对R在心理学中的应用感兴趣的研究者
- 正在复习26心统下期中考试的人

## 📊 数据来源说明

- **示例数据（.sav/.xlsx）**：第一版的数据来自课程助教老师们提供的上机材料，已获得助教老师们授权，可在本教学项目中公开使用。但是在quarto生成的书籍中，所有的数据由我使用set.seed替换为模拟数据。所有数据仅为教学示例，不代表实际情况。

- **课程pdf截屏（.png）**：来自课程使用的ppt文件，已经获得授权，可以在本教学项目中公开使用。出于多方面考虑，在quarto书籍中删除了所有的截图。

## 📁 目录结构

```markdown
Psych-Stats-R-2/
├── 📄 _quarto.yml              # 🔧 项目核心配置：定义书籍结构、输出格式、GitHub Pages
├── 📄 _common.R                # 🛠️ R 包统一管理：所有章节共享的包加载和环境设置
├── 📄 index.qmd                # 🏠 在线书籍的首页（项目概览、导航）
├── 📄 intro.qmd                # 📖 引言/序言（可选）
├── 📄 summary.qmd              # 🏁 总结与展望
├── 📄 references.qmd           # 📚 参考文献页面
├── 📄 references.bib           # 📚 BibTeX 格式的参考文献库文件
├── 📄 cover.png                # 🎨 书籍封面图片
├── 📄 psych-stats-book.Rproj   # 📌 RStudio 项目文件，一键打开项目
├── 📄 .gitignore               # 忽略规则
├── 📄 README.md                # 📄 项目说明文档
├── 📂 chapters/                # ✍️ 核心内容章节（.qmd 源文件）
│   ├── 📄 01-non-parametric-test.qmd
│   ├── 📄 02-anova.qmd
│   ├── 📄 03-logistic-regression.qmd
│   └── 📄 04-multiple-regression.qmd
├── 📂 data/                    # 📊 所有原始数据
│   ├── 📂 sav_files/           #   SPSS 格式 (.sav) 文件
│   └── 📂 excel_files/         #   Excel 格式 (.xlsx) 文件
├── 📂 images/                  # 🖼️ 图片资源
├── 📂 src/                     # ⚙️ 辅助脚本
└── 📂 _book/                   # 🚀 书籍渲染输出
```

## 🚀 快速开始

### 1. 在线浏览（无需安装任何东西）

👉 **[点击这里阅读在线书籍](https://bailihan14.github.io/Psych-Stats-R-2/)**

支持左侧导航目录、全文搜索、代码一键复制、PDF/EPUB 下载。

### 2. 本地运行

**环境要求：**
- R (≥ 4.0)
- RStudio（推荐）

**步骤：**
```bash
# 1. 克隆仓库
git clone https://github.com/BAILIHAN14/Psych-Stats-R-2.git
cd Psych-Stats-R-2

# 2. 在 RStudio 中打开 psych-stats-book.Rproj

# 3. 安装依赖包（首次运行需要）
# 打开 R Console，运行：
# install.packages(c("here","haven","readxl","car","DescTools",
#   "rstatix","tidyverse","bruceR","psych","lme4","lmerTest",
#   "emmeans","effectsize","HH","irr","agricolae","ggplot2",
#   "gridExtra","ppcor","aod","lmtest","ResourceSelection",
#   "pscl","multcomp","mvnormtest","heplots","BSDA"))

# 4. 渲染全书
# 在 RStudio Terminal 中运行：
quarto render
```
渲染完成后，在项目根目录下的 _book/ 文件夹中找到 index.html 打开即可。

### 本地运行

1. **克隆仓库：**
   ```bash
   git clone https://github.com/BAILIHAN14/Psych-Stats-R-2.git
   cd Psych-Stats-R-2


### 在线查看

[![View HTML Document](https://img.shields.io/badge/View_Live-HTML-0072C6?style=for-the-badge&logo=html5)](https://bailihan14.github.io/Psych-Stats-R-2/PsychSta-2.html)

## 致谢
-感谢26春心理统计2的李健老师;
-感谢2026春-心理统计2-三教403的助教老师们，他们为我提供了宝贵的参考数据，尤其感谢张嘉欣助教老师，她解答了我整理文档时面临的困惑；
-感谢deepseek，没它我学不会git,latex,r还有各种各样的小玩意;
-感谢江一平同学，没他的提醒我会忘了收拾仓库。
-尤其感谢我的小电脑，没它就没有这一切。

## 👤 作者
```markdown

- **姓名：** Alieen 或者 Ayaman Orken
- **GitHub：** [@BAILIHAN14](https://github.com/BAILIHAN14)
- **邮箱：** 2500013771@stu.pku.edu.cn
```

## 其他
本仓库会不定期地更新后续的上课内容，也会不定期的更新有意思的r和统计学。文件篇幅较大，受限于本人能力，无法保证文件完全没有差错，还请各位指出错误、提供意见。

**如果这个文件对你有用，请点击小星星⭐**
**如果这个文件帮助到了你，我很开心**
