# 统计力学笔记 — Pathria & Beale《Statistical Mechanics》第三版

本项目是对 **Pathria & Beale《Statistical Mechanics》Third Edition** 的 LaTeX 学习笔记，使用 XeLaTeX + ctex 编译。

## 项目结构

```
.
├── main.tex          # 主文件
├── chap1.tex         # 第 1 章
├── chap2.tex         # 第 2 章
├── ...
├── chap17.tex        # 第 17 章
├── apendA.tex        # 附录 A
├── apendB.tex        # 附录 B
├── images/           # 图片资源
├── [Pathria_R.K.,_Beale_P.D.]_Statistical_mechanics.pdf  # 原书 PDF
└── README.md
```

## 编译方式

```bash
xelatex main.tex
```

## 开发流程（Git 工作流）

### 日常开发三板斧

修改代码后，依次执行以下命令：

```powershell
# 1. 查看当前修改了哪些文件
git status

# 2. 将所有修改加入暂存区
git add .

# 3. 提交到本地仓库
git commit -m "描述你做了什么修改"

# 4. 推送到 GitHub
git push
```

### 快捷版（三行搞定）

```powershell
git add .
git commit -m "更新内容描述"
git push
```

### 常用 Git 命令速查

| 命令 | 作用 |
|------|------|
| `git status` | 查看当前修改状态 |
| `git add .` | 暂存所有修改 |
| `git add 文件名` | 暂存指定文件 |
| `git commit -m "信息"` | 提交到本地仓库 |
| `git push` | 推送到 GitHub |
| `git log --oneline` | 查看提交历史 |
| `git diff` | 查看具体修改内容 |
| `git pull` | 拉取远程最新代码 |

### 注意事项

- **频繁提交**：每完成一个小改动就 commit，不要在本地积攒大量修改。
- **清晰的 commit 信息**：用简洁的语言描述本次修改内容，避免使用 `update`、`fix` 等模糊描述。
- **及时 push**：提交后尽快推送到 GitHub，相当于远程备份，防止本地数据丢失。
