# 湖南大学课程论文LaTeX模板（非官方）
本项目是湖南大学课程论文 LaTeX 模板（非官方）。需要注意的是，该模板主要用于综合性论文，并非按照学位论文撰写规范编写，如有学位论文写作需求可移步
[hnuthesis](https://github.com/yusanshi/hnuthesis)。

**模板的展示效果**可以下载 [GitHub Releases](https://github.com/zcyeee/HNU_LaTeX_Template/releases) 中的示例文档 `guide.pdf` 查看。

因本人能力、精力有限，模板难免会存在许多不足。如果你有良好意见和改进建议，可以在顶栏的问题（Issues）一栏中提出，也可以联系：chenyang@hnu.edu.cn。


## 主要文件介绍

- `config.cls`：模板配置文件。
  
- `License`：许可证文件。

- `references.bib`：参考文献列表。

- `guide.tex`：使用指南/示例文档。（仅起到介绍示范作用，使用时可删除）

- `main.tex`：**主文件，编译入口**。

- `figures/`：储存编译中会用到的图片。

- `fonts/`：储存编译中需要额外用到的字体。


## 如何使用该模板

### 1.Overleaf（推荐）

[Overleaf](https://www.overleaf.com/) 是一个线上 LaTeX 编辑器，可以在不安装任何工具的情况下编写 LaTeX 文档，同时也可以和其他人共享文档，共同编辑。该模板便是在 Overleaf 上整理编写完成并测试通过的。

需要使用时可以直接在 Overleaf 的 Templates 中搜索 “湖南大学课程论文模板”，或者点击 [链接](https://www.overleaf.com/latex/templates/hu-nan-da-xue-ke-cheng-lun-wen-mo-ban-cn/rrgftptzpzss) 跳转。

但由于 Overleaf 审核较慢，模板若有更新不能及时同步，因此也可以在 [GitHub Releases](https://github.com/zcyeee/HNU_LaTeX_Template/releases) 中下载模板源文件 `hnu_template.zip` ，在 Overleaf 中上传该压缩文件以创建一个新项目。注意，在正式编译前，需要先在 Overleaf 界面左上角点击 "Menu"：

- **选择 "Compiler" 为 "XeLaTeX"**
- **选择 "TeX Live version" 为 "2023"** 




### 2.本地编译

在本地编译时需要配置好 LaTeX 环境，并推荐使用 Visual Studio Code 配合 LaTeX Workshop 插件作为编辑器。

模板编译顺序为：XeLaTeX -> BibTeX -> XeLaTeX -> XeLaTeX。

由于能力与时间有限，**作者并未在本地编译测试成功**。若有同学在本地测试成功，同样欢迎联系：chenyang@hnu.edu.cn。






