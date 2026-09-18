# Frontend Less AI Tone

一个面向通用前端工作的 Skill：让页面读起来、看起来像具体产品，而不是通用 AI 落地页或仪表盘。

它管文案、视觉方向、层级和常见 AI 默认皮的否决。可以写 HTML、CSS、JS、React。先定一个主行动和一个视觉记忆点，再写句子和样式。事实只来自给定材料；没有的数字、客户、认证不要编。

受约束的生成器（只许改槽位、不许吐 CSS）应使用项目自己的叠加层，不要用本 Skill 硬写样式。

## 适用范围

- 落地页、营销站、后台、表单、空状态、设置页、组件
- 用户说太像模板、太 AI、去 AI 味、好看一点、专业一点
- 对照「给谁都那一套」的默认皮：Inter / 紫黑渐变 / 三列卡片 / 假 99.9%

Skill 不绑定具体框架、设计系统或仓库结构。字体名不是授权；只用项目已有、系统栈或已核许可的字体。

## 使用

安装：

```bash
npx skills add a1024053774/frontend-less-ai-tone-skill@frontend-less-ai-tone -g -y
```

然后直接告诉 Agent：

```text
用 frontend-less-ai-tone 帮我做这一页：读者是谁、主行动是什么、已知事实有哪些。
```

同一份 brief 的未用 / 已用对照见 [`frontend-less-ai-tone/examples.md`](frontend-less-ai-tone/examples.md)，完整 HTML 在 [`frontend-less-ai-tone/examples/`](frontend-less-ai-tone/examples/)。

## 设计依据

文案层改编自 [lieflat-less-ai-tone](https://github.com/larashero3-dotcom/lieflat-less-ai-tone)（MIT）。样子层参考 [Anthropic frontend-design](https://github.com/anthropics/skills/tree/main/skills/frontend-design)（Apache-2.0）。来源钉死见 [`frontend-less-ai-tone/SOURCE.md`](frontend-less-ai-tone/SOURCE.md)。

仓库地址：[github.com/a1024053774/frontend-less-ai-tone-skill](https://github.com/a1024053774/frontend-less-ai-tone-skill)

## License

MIT. Third-party notices: [NOTICE](NOTICE).
