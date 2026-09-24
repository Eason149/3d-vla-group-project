# 3D-VLA Group Project

组内用于学习、复现和讨论 3D-VLA 的项目仓库。

## 目录

- `meeting-01/`：第一次组会的 LaTeX Beamer 源文件与编译结果
- `references/`：论文与参考资料
- `assets/`：后续组会可复用的图片与素材
- `notes/`：阅读笔记和实验记录
- `experiments/`：复现代码、配置和结果

## 编译第一次组会

推荐使用 XeLaTeX：

```bash
cd meeting-01
xelatex main.tex
xelatex main.tex
```

也可以使用 Tectonic：

```bash
tectonic main.tex
```

## 协作约定

1. 每个实验建立独立分支。
2. 提交中不要包含数据集、模型权重和密钥。
3. 图表和结论需在同一文件或幻灯片中标注来源。
4. 合并前写清环境、命令、主要结果与已知问题。

## 核心论文

H. Zhen, X. Qiu, P. Chen, J. Yang, X. Yan, Y. Du, Y. Hong, and C. Gan, “3D-VLA: A 3D Vision-Language-Action Generative World Model,” in *Proceedings of the 41st International Conference on Machine Learning*, vol. 235, 2024, pp. 60258–60276.

