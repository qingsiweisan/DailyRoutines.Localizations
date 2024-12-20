## Daily Routines 本地化文本存储仓库

**源语言文件**: `ChineseSimplified.json` 
**译文**: 其他以 `.json` 结尾的语言文件

### **提交原文/译文:**

- 修改对应的 `.json` 文件, 提交 **Pull Request**, 合并后自动工作流会将原文与译文上传至 [Crowdin](https://zh.crowdin.com/project/dalamud-dailyroutines)
- 在 [Crowdin](https://zh.crowdin.com/project/dalamud-dailyroutines) 上直接提交对应语言的译文, 每天 0 点与新版本发布前, 自动工作流会从 [Crowdin](https://zh.crowdin.com/project/dalamud-dailyroutines) 拉取一次译文 (不支持原文提交)

### **翻译讨论:**

- 请直接新建一个 Issue, 以 `[对应语言] 主题 `的格式命名标题 (例: `[简体中文] 对 XXX 的用词不太恰当`)

### **注:**

- 若不想出发原文/译文上传工作流, 请在 **Commit Title** 中包含 `[skip-upload]` 的信息 **(大小写敏感)**