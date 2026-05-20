# My Skills

TRAE SOLO 技能合集。

## 包含的技能

| 技能 | 说明 | 安装路径 |
|------|------|---------|
| [concept-fable](concept-fable/) | 用寓言故事学概念。支持科幻、武侠、童话等多种风格，内置猜谜模式和隐喻解析。 | `.trae-cn/skills/concept-fable/` |

## 安装

每个技能是独立的文件夹。把需要的文件夹复制到 TRAE SOLO 的 skills 目录：

- Windows: `%USERPROFILE%\.trae-cn\skills\`
- macOS/Linux: `~/.trae-cn/skills/`

也可以直接 clone 整个仓库，然后建软链接：

```bash
git clone https://github.com/2017java/myskills.git
# Windows
mklink /D "%USERPROFILE%\.trae-cn\skills\concept-fable" "myskills\concept-fable"
# macOS/Linux
ln -s myskills/concept-fable ~/.trae-cn/skills/concept-fable
```

## 许可

各技能独立许可，详见各自目录。
