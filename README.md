# Opus 视频风格资料库

117 个风格条目：99 个 Lemo 影片风格、18 个手作 MV 引擎。含案例图、作者视频链接、完整提示词与逐项注意事项。

- [打开在线图册](https://limingzhaox.github.io/opus-video-style-library/)
- [给其他 AI 的入口](https://limingzhaox.github.io/opus-video-style-library/llms.txt)
- [给其他 AI 的三套使用指令](https://limingzhaox.github.io/opus-video-style-library/AI使用说明.md)
- [机器索引](https://limingzhaox.github.io/opus-video-style-library/styles.json)
- [完整提示词索引](https://limingzhaox.github.io/opus-video-style-library/完整提示词总册.md)
- [使用指南](https://limingzhaox.github.io/opus-video-style-library/使用指南.md)
- [作者署名与许可](https://limingzhaox.github.io/opus-video-style-library/ATTRIBUTION.md)

## 内容与来源

Lemo STYLE.md 保留完整作者原文；18 项手作模板根据引擎说明整理，并非作者原始对话。中文任务模板由资料库整理。使用时另行克隆对应完整上游工程，交给可运行代码的 AI，并检查环境、声音、素材与短片预览。

主要来源：[Lemo-Opuscar by Lemomo (LemoLab)](https://github.com/lemomo-ai/lemo-opuscar)、[Miranda Dixon-Luinenburg](https://github.com/cyborggirl963/opus-5.5-music-video-art-styles)。Lemo 文档及其改编按 CC BY-NC 4.0 非商业共享，为自己的影片（含商业、客户影片）使用另有额外许可；代码为 MIT，示例图片可授权部分为 CC BY 4.0。手作库保留 MIT。图片经过缩放编排，第三方素材、六项旁白（含整片复用）、Clawd 与界面商标另有限制，详见署名页。吉祥物录屏与流场风线案例仅提供作者链接及标注清楚的查看入口占位图。

## 仓库与部署

site.zip 是可审查、可离线解压的完整静态资料包，下载解压后打开 index.html。GitHub Actions 解压后部署 GitHub Pages。每个 prompts/*.md、JSON 与原文快照都可从站点独立读取，无需运行网页脚本。包含公开文档、来源版本、许可证、构建与检查脚本；不含原始 PDF、个人修改目录、凭据或机器配置。

每周二 10:00（Asia/Shanghai）由本地 Codex 维护任务核对上游，审查变化、更新资料包并部署。维护需要本机与 Codex 运行。静态网站部署后不依赖本机开机，外部访客仍可访问上次成功部署的版本。
