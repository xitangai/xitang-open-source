# 飞书文章发推特

`xys-feishu-to-x` 是西堂 / 西羊石整理的 Codex Skill。给它一个自己的飞书文章链接，它会读取全文与图片、视频、提示词，自主判断是否需要轻改写，整理后发布到本人登录的 X 账号，再返回真实链接和检查结果。

完整文章默认使用 X Articles，保留作者口吻和关键素材；支持查重、中断恢复，以及只看稿或保存平台草稿。

## 从 GitHub 安装

在本地 Codex 中输入：

```text
请安装这个 GitHub 目录中的 xys-feishu-to-x Skill：
https://github.com/xitangai/xitang-open-source/tree/main/skills/xys-feishu-to-x
本次只安装，不发布文章。如果已有同名 Skill，先检查版本与本地修改。
```

也可以下载仓库，将本目录完整交给 Codex 安装。保留 `SKILL.md`、`agents/`、`references/` 和使用说明，不要只复制一个文件。

## 使用

```text
使用 $xys-feishu-to-x，把这篇飞书文章整理后直接发布到我的推特：
【飞书链接】
```

如果只想先看稿：

```text
使用 $xys-feishu-to-x 处理这个飞书链接，先给我看稿，不发布：
【飞书链接】
```

## 使用条件

- 在自己的电脑上运行 Codex，并登录自己的飞书和 X 账号。
- 当前 Codex 会话具备操作该浏览器和上传文件的工具；本 Skill 不自带浏览器服务。
- 对飞书正文与素材有访问权限，X 账号能使用 Articles。实际能力会在运行时检查。

不需要向 Skill 提供密码或 Cookie。需要登录时由本人完成；缺少工具、权限或账号权益时会说明具体限制并保留已完成进度。

## 说明与验证范围

完整安装、草稿模式和恢复说明见 [使用说明](使用说明.md)，执行流程见 [SKILL.md](SKILL.md)。

公开前已完成 Skill 格式、文件引用、分发文件和离线场景检查；尚未在其他成员的电脑上完成真实发布验收。安装成功不等于本机登录、上传和发布环境已经验证。

## 许可

本 Skill 由西堂 / 西羊石整理，使用 [MIT 许可证](LICENSE)。来源仓库：[xitangai/xitang-open-source](https://github.com/xitangai/xitang-open-source)。

许可证适用于本目录的 Skill 文本和说明，不赋予使用者对输入文章、媒体或第三方平台的额外权利。发布时使用自己有权公开的内容，并保留必要署名与合作披露。
