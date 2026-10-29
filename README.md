# 西堂开源 · Xitang Open Source

西堂的 Skills、工具、模板与使用示例，统一在一个仓库中整理。

作者与维护者：**西堂（Xitang）**

个人网站：[xitangai.com](https://xitangai.com/) · GitHub：[xitangai](https://github.com/xitangai)

## 目录

| 目录 | 内容 |
| --- | --- |
| [skills/](skills/) | 可安装的 AI Skills，每个 Skill 直接放在独立子目录中 |
| [tools/](tools/) | 脚本、小工具与可独立运行的应用，待收录 |
| [templates/](templates/) | 可复用模板，待收录 |
| [examples/](examples/) | 可公开的输入输出示例与演示，待收录 |

```text
xitang-open-source/
├── skills/
│   └── xys-feishu-to-x/
├── tools/
├── templates/
└── examples/
```

## 已收录的 Skills

| Skill | 用途 | 运行环境 | 许可证 |
| --- | --- | --- | --- |
| [飞书文章发推特](skills/xys-feishu-to-x/) | 读取飞书全文与素材，自主轻改写，发布到本机登录的 X 账号，并回查结果 | 本地 Codex，需可操作已登录浏览器和上传文件的工具 | [MIT](skills/xys-feishu-to-x/LICENSE) |

## 安装与使用

把具体 Skill 的 GitHub 目录链接交给 Codex，例如：

```text
请从下面的 GitHub 目录安装 xys-feishu-to-x Skill：
https://github.com/xitangai/xitang-open-source/tree/main/skills/xys-feishu-to-x
本次只安装，不发布文章。如果已有同名 Skill，先检查版本与本地修改。
```

安装后的使用方式、所需账号与工具能力，见各 Skill 的说明。Skill 提供操作流程，不附带账号、登录状态或浏览器服务。

## 来源与许可

- 西堂个人作品使用 `xitang-*`；西羊石团队作品保留 `xys-*`，各作品说明实际作者与贡献者。
- 每个作品独立声明许可证，以其目录中的 `LICENSE` 和来源说明为准；本仓库不为未来收录的内容统一授予许可。
- 本次收录的 `xys-feishu-to-x` 由西堂 / 西羊石整理并以 MIT 许可证开源。许可证不涵盖使用者处理的文章、图片、视频或第三方平台服务。
- 改编作品保留原作者、来源与原许可证，并说明修改内容。仅收录选定的公开版本，不同步私人知识库、账号凭证或业务运行记录。
