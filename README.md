# xiu86 Codex 插件市场

这是 xiu86 维护的 Codex 插件市场源。

## 插件列表

| 插件 | 说明 |
| --- | --- |
| `api-blackbox-tester` | 编排接口黑盒测试的方案、执行和报告，并将三阶段结果写入 Markdown 文件。 |

## 使用方式

在 Codex CLI 中添加本市场源：

```bash
codex plugin marketplace add xiu86/codex-plugins
```

添加后重新打开 Codex 会话，即可使用市场中的插件能力。

## 目录结构

```text
plugins/
└── api-blackbox-tester/
    ├── .codex-plugin/plugin.json
    ├── skills/
    └── README.md
```
