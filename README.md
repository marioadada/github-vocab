[README.md](https://github.com/user-attachments/files/28694400/README.md)
# GitHub & Git 高频词交互式学习卡

> 110 个 GitHub & Git 高频英文词汇，边学英语边熟悉操作。
>
> 在线地址：https://marioadada.github.io/github-vocab/

---

## 收录内容

| 分类 | 词汇数 | 核心内容 |
|------|--------|----------|
| 基础操作 | 11 | init、clone、add、commit、push、pull、fetch、status、log、diff、show |
| 分支管理 | 9 | branch、checkout、switch、merge、rebase、cherry-pick、conflict、fast-forward、detached HEAD |
| 撤销恢复 | 9 | reset、revert、stash、restore、clean、amend、reflog、bisect、blame |
| 远程协作 | 6 | remote、origin、upstream、downstream、fork、force push |
| GitHub 核心 | 11 | repository、issue、PR、review、star、watch、notification、comment、approve、request changes、close/reopen |
| GitHub 自动化 | 7 | action、workflow、runner、job、step、artifact、deploy |
| 版本发布 | 6 | release、tag、draft、pre-release、changelog、semver |
| GitHub 项目管理 | 8 | milestone、label、assign、project、wiki、gist、discussion、pin |
| 高级概念 | 10 | HEAD、SHA、tracked、staged、modified、index、working tree、bare、squash、hook |
| 配置与忽略 | 5 | .gitignore、.gitattributes、CODEOWNERS、README、license |
| 权限协作 | 6 | collaborator、permission、branch protection、status check、CONTRIBUTING、template |
| 组织管理 | 5 | organization、team、admin、maintainer、contributor |
| 安全认证 | 5 | token、SSH key、credential、authentication、authorization |
| GitHub Pages | 1 | GitHub Pages |
| 新手常见问题 | 4 | Clone vs Fork、HTTPS vs SSH、Public vs Private、GUI vs CLI |

**总计：110 个词汇，15 个分类**

---

## 六大学习模式

### 1. 浏览模式
- 侧边栏分类导航，一键筛选
- 搜索框支持中英文检索
- 难度标签筛选（入门 / 进阶）
- 点击卡片展开：音标、词性、释义、Git 命令实操、记忆技巧、随堂测验
- 标记已掌握，进度实时保存
- **发音朗读**：每个词右上角 🔊 按钮，点击朗读英文
- **个人笔记**：词卡底部可写笔记，自动保存
- **命令速查面板**：按场景快速查找命令（撤销、同步、分享、历史、分支、储藏）

### 2. 每日挑战
- 从 110 题中随机抽取 5 道
- 实时计时，答完出成绩
- 圆环进度条 + 用时统计 + 动态评语
- 记录历史最高分

### 3. 命令模拟器
- 10 个真实 Git 场景（初始化、克隆、暂存、提交、推送、拉取、分支、合并、修正、储藏）
- 输入命令，系统判断对错
- 可查看提示，答错显示正确答案

### 4. 错题本
- 自动收集所有答错的题
- 显示原题 + 你的错选（红）+ 正确答案（绿）
- 支持重新测验错题

### 5. 我的笔记
- 汇总所有写过笔记的词汇
- 可查看、编辑每个词的笔记

### 6. 学习趋势
- 最近 7 天柱状图（CSS 纯实现）
- 三色柱：已掌握（绿）/ 已测验（黄）/ 正确（紫）
- 文字统计：本周掌握 X 词、答题 Y 道、正确率 Z%

---

## 快捷键

| 按键 | 功能 |
|------|------|
| `/` | 聚焦搜索框 |
| `j` / `k` | 下一个 / 上一个卡片 |
| `Enter` | 展开 / 收起当前卡片 |
| `l` | 标记当前卡片为已掌握 |
| `Esc` | 取消搜索聚焦 |
| `1` ~ `6` | 切换六大模式 |

---

## 数据说明

- **存储位置**：浏览器 localStorage（纯本地，不上传）
- **键名**：
  - `gh_learned` — 已掌握词汇
  - `gh_quiz` — 测验结果
  - `gh_notes` — 个人笔记
  - `gh_challenge_best` — 挑战最高分
  - `gh_daily` — 每日学习统计
- **清除数据**：浏览器设置 → 隐私与安全 → 清除网站数据

---

## 隐私说明

- 无后端、无 Cookie、无数据收集
- 纯静态网页，所有数据仅存于本地浏览器
- 代码开源（Public 仓库），不暴露个人学习数据

---

## 技术栈

- HTML + CSS + Vanilla JavaScript
- Web Speech API（发音朗读）
- localStorage（数据持久化）
- GitHub Pages（静态托管）

---

## 本地使用

直接下载 `github-vocab-pro.html`，用浏览器打开即可。无需联网，数据自动保存。

---

## 更新日志

- **v1.0** — 发布 Pro 版，110 词、6 大模式、发音、笔记、快捷键、趋势图
- **v0.9** — 110 词完整版，15 分类，测验 + 掌握标记 + 搜索筛选
- **v0.1** — 每日打卡原型，Day 1 测试

---

> 作者：marioadada
> 构建工具：WorkBuddy
