# Photo English Poster · 照片变英语学习海报

把一张生活照片，变成一张漂亮又实用的双语英语学习海报。

不仅识别物品，还把真实场景转化为能开口、能写作的表达。适合教师备课、学生自学，以及小红书风格的英语学习内容制作。

## 下载与使用

[下载 skill 压缩包](photo-english-poster.zip)

解压后，将 `photo-english-poster` 文件夹交给支持 skills 的助手安装，或放入该工具的 skills 目录。也可以直接让助手读取本仓库的 [SKILL.md](SKILL.md)。

上传一张照片，然后输入：

```text
使用 $photo-english-poster，把这张照片制作成 B1 双语英语学习海报。
```

继续制作同系列时：

```text
接下去生成这张照片的海报，延续上一张的系列风格。
```

可以指定学习水平和风格，例如“按高中生水平制作”“改成 B2”“清爽杂志风”。默认使用 B1 水平、优雅实用的小红书风格和竖版海报布局。

## 一张海报包含什么

| 板块 | 内容 |
| --- | --- |
| vocabulary | 6–10 个高价值词汇或短语，配中文含义 |
| collocations | 5–8 组自然搭配，帮助成组记忆 |
| example sentences | 5–8 个与照片相关的双语例句 |
| scene description | 一段整合目标表达的场景描述及中文翻译 |
| speak & write | 3 个带提示词的口说／写作任务 |
| study tip | 提醒学习者在真实情境里使用单词 |

默认交付海报图片、可编辑文案、设计说明和生成提示词。

## 场景示例

**餐厅入座：a little table, a lot to say**

从花卉餐盘、玻璃杯和菜单出发，学习 `browse the menu`、`order a drink`、`ask for a recommendation`。配色可以呼应照片里的奶油白、墨绿和柔粉。

**烤鸭上桌：wrap, share & enjoy**

从竹蒸笼、薄饼和烤鸭出发，学习 `wrap duck in a pancake`、`roll up a pancake`、`help yourself to some duck`。视觉采用竹棕、青花蓝与菜叶绿。

更多设计细节见 [design-guide.md](references/design-guide.md)。这些是参考方向；新照片会使用适合自身场景的内容和配色。

## 运行条件与边界

这是一个提示词与工作流 skill，不是独立应用。需要支持读取 skill 的 AI 助手；输出最终图片还需要该环境提供图像生成功能。没有图像生成功能时，会输出完整文案和排版说明。

不附带 API 密钥，不依赖原作者电脑的文件路径。生成图片中的中英文需要进行视觉校对。不会自动发布到社交平台。仓库包含可复用流程和文字示例，不包含用户原始照片。

## 文件结构

```text
SKILL.md                    核心工作流
references/design-guide.md  两种场景的设计参考和提示词框架
photo-english-poster.zip    可分发的 skill 安装包
LICENSE                     MIT 许可证
```

## English overview

Photo English Poster is a reusable AI skill that turns everyday photos into practical bilingual English–Chinese learning posters. It combines vocabulary, collocations, contextual sentences, a short scene description, and three speaking/writing tasks. Default level: CEFR B1. A compatible image-generation tool is required for rendered posters; otherwise the skill delivers copy and a layout brief.

## License

The skill instructions and documentation are released under the [MIT License](LICENSE). Users are responsible for having permission to use their own input photos.
