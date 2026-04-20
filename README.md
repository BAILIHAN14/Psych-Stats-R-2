# Psych-Stats-R-2 · 心理统计R语言教学文档

![R](https://img.shields.io/badge/R-4.0%2B-blue) ![License]
(https://img.shields.io/badge/License-MIT-green)


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

- **多数课程上机示例数据（.sav）（.xlsx）**：来自课程助教老师们提供的上机材料，已获得助教老师们授权，可在本教学项目中公开使用。数据仅为教学示例，不代表实际情况。
- **部分（.sav）**：由我使用 `set.seed()` 生成的教学用模拟数据。不代表实际情况。
- **课程pdf截屏（.png）**：来自课程使用的ppt文件，已经获得授权，可以在本教学项目中公开使用。

## 📁 目录结构

```markdown
Psych-Stats-R-2/
├── 📄 README.md # 项目说明文档
├── 📄 .gitignore # Git 忽略规则
├── 📂 docs/ # 生成的文档和图片
│ ├── 📄 PsychSta-2-demo.html # 主要HTML文档
│ └── 📂 images/ # 所有图表图片
├── 📂 data/ # 原始数据文件
│ ├── 📂 sav_files/ # SPSS .sav 文件
│ └── 📂 excel_files/ # Excel 文件
├── 📂 src/ # 源代码
│ └── 📄 PsychSta-2-demo.Rmd # R Markdown 源文件
```
## 🚀 如何使用

### 环境要求
- R (≥ 4.0)
- RStudio（推荐）
- 部分R包（已经在.rmd文件中展示）


### 文件组成
- PsychSta-2.Rmd为主要的文件，请使用Rstudio打开。默认以visual模式打开，切换到source可能会导致排版错乱。内容涵盖了统计学方法、r语言函数等内容。有可以运行的r的代码块，可以自行修改参数等内容。运行代码块前请清空工作台。有大纲分类，但排版可能会相对的简陋。
- PsychSta-2.html 为.html格式文件，内容与.Rmd文件内容一致。排版更加清晰美观，添加了可以自动跳转的目录，也可以查看现成的运行结果。
- 其余的文件为.Rmd运行所需要的文件。



### 本地运行

1. **克隆仓库：**
   ```bash
   git clone https://github.com/BAILIHAN14/Psych-Stats-R-2.git
   cd Psych-Stats-R-2


### 在线查看

[![View HTML Document](https://img.shields.io/badge/View_Live-HTML-0072C6?style=for-the-badge&logo=html5)](https://bailihan14.github.io/Psych-Stats-R-2/PsychSta-2.html)

## 致谢
感谢26春心理统计2的李健老师;感谢2026春-心理统计2-三教403的助教老师们，他们为我提供了宝贵的参考数据，尤其感谢张嘉欣助教老师，她解答了我整理文档时面临的困惑；感谢deepseek，没它我学不会git,latex,r还有各种各样的小玩意;感谢江一平同学，没他的提醒我会忘了收拾仓库。
尤其感谢我的小电脑，没它就没有这一切。

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
