# 东方影像创作插件

将可复用的影像创作方法整理为 Codex 插件。目前收录 **东方极简巨构**（`oriental-megastructure`，v0.1.0）。

## 东方极简巨构

根据主题、场景或参考图，生成、诊断和改写可直接复制的 Midjourney 英文提示词。

- 单体、纪念碑尺度的唐宋风格建筑。
- 极小人物参照、大面积留白、简洁轮廓。
- 朱红、黑白、淡青与少量古金构成的克制色彩。
- 默认竖屏 9:16，多场景请求注重空间和几何差异。

插件只生成或分析提示词，不提交 Midjourney 任务，也不直接生成图片。插件本身没有 MCP、外部应用连接或 API 密钥配置；实际出图由使用者在 Midjourney 中完成。

## 安装

需要已登录、支持插件市场的 Codex 客户端，以及可用的 Codex CLI。在终端运行：

```sh
codex plugin marketplace add wangliangzhong75-code/creative-plugins
```

打开桌面端的插件目录，选择 **东方影像创作插件**，安装 **东方极简巨构**。若列表没有刷新，重启桌面端后查看。

## 使用示例

```text
使用东方极简巨构，生成四组不同场景的 Midjourney 竖屏提示词：云海天门、月下长桥、深空祭坛、雨中巨殿。
```

## 更新

```sh
codex plugin marketplace upgrade wang-creative-plugins
```

作者：Wang Liangzhong。
