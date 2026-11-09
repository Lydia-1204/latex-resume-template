# LaTeX 简历模板

## 在 Overleaf 中使用

1. 将模板文件打成 ZIP，在 Overleaf 选择 **New Project → Upload Project**。将三个简历入口文件和 `resume.cls` 放在项目根目录。[上传项目](https://docs.overleaf.com/managing-projects-and-files/uploading-a-project)
2. 在 **Settings → Compiler** 中将编译器设为 **XeLaTeX**，并在 **Main document** 中选择一个入口。[编译器设置](https://docs.overleaf.com/getting-started/recompiling-your-project/selecting-a-tex-live-version-and-latex-compiler) · [主文档设置](https://docs.overleaf.com/getting-started/recompiling-your-project/the-main-document)

   | 入口文件 | 版式 |
   | --- | --- |
   | `resume.tex` | 英文，无照片 |
   | `resume_photo.tex` | 英文，带照片栏 |
   | `resume-zh_CN.tex` | 中文，带照片栏 |

3. 替换选定文件中方括号内的占位内容，按需复制或删除项目条目，然后点击 **Recompile**。正文中的 `&`、`%` 和 `_` 分别写成 `\&`、`\%` 和 `\_`。
4. 带照片栏的版本默认显示占位框。上传名为 `photo.jpg` 的照片到项目根目录即可替换。

## 来源与许可

本项目改编自 Bill Ryan 的 LaTeX 简历模板，保留上游 MIT 许可证全文，见 [`LICENSE`](LICENSE)。上游说明列出了 `simple-resume-cv` 和 ShareLaTeX 的简历类教程等参考资料。[上游模板与致谢](https://github.com/billryan/resume/tree/zh_CN)

模板从 Overleaf 的 TeX Live 加载 TeX Gyre Termes、Fandol 中文字体和 Font Awesome 图标。这些依赖分别适用各自的许可，由 TeX Live 提供。[TeX Gyre](https://ctan.org/pkg/tex-gyre) · [Fandol](https://ctan.org/pkg/fandol) · [Font Awesome LaTeX 宏包](https://ctan.org/pkg/fontawesome) · [Font Awesome 4 字体许可](https://fontawesome.com/v4/license/)
