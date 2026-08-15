# nax-ui skills

面向 **uni-app x（uvue）** 组件库 nax-ui 的 Agent 技能包，帮助 AI 编码助手准确使用 nax-ui 的 50 个 `nax-*` 组件编写页面。

## 安装

```text
npx skills add <owner>/nax-ui-skills
```

安装后，AI 代理（Claude Code / Cursor / OpenCode 等）在遇到 nax-ui 相关任务时会自动加载本技能：

- 组件速查索引（50 个组件分类一句话说明）
- 每组件 API 参考（Props / Events / Slots / Methods / 用法示例）
- 主题接入指南（nax-ui-theme、CSS 变量、暗色模式）

## 使用场景

- 在 uni-app x 项目中用 nax-ui 编写页面（表单 / 列表 / 弹窗 / 导航 / 反馈）
- 查询 nax-* 组件的 props、事件、插槽用法
- 配置 nax-ui 主题与品牌色

## 技能结构

```
SKILL.md                      # 技能入口：使用流程 + 代码规范
references/
  component-index.md          # 50 组件分类速查
  theme-guide.md              # 主题接入指南
  components/nax-*.md         # 各组件 API 参考卡
```

## 手动安装

不使用 skills CLI 时，也可以将本仓库 `SKILL.md` 与 `references/` 复制到：

- Claude Code: `~/.claude/skills/nax-ui/`
- OpenCode: `~/.agents/skills/nax-ui/`

## 相关项目

- [nax-ui](https://github.com/<owner>/nax-ui) — uni-app x UI 组件库本体

## License

MIT
