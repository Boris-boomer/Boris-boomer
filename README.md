### Boris · AI Agent Systems Engineer

独立开发者，专注 **LLM Agent 运行时、浏览器自动化、桌面插件生态**。
擅长把"能跑的原型"打磨成"敢长期挂机的产品"——架构设计、协议逆向、故障根因定位、工程化交付。

<!-- 关于链接：<https://boris-boomer.github.io> 等简历页上线后，把下方"🌐 简历"那行取消注释 -->

---

#### 近期在做什么

| 项目 | 一句话 |
| :--- | :--- |
| **[ShipSignal](https://github.com/Boris-boomer/shipsignal)** | 本地优先的独立开发者决策助手 · Tauri 2.0 · 5MB 安装包 · 冷启动 <1s |
| **[Hermes-Browser](https://github.com/Boris-boomer)** | 把 5 个网页版 AI 封装为 OpenAI 兼容 API / HTTP / MCP · 88 测试全绿 |
| **[semantic-loop-audit](https://github.com/Boris-boomer/semantic-loop-audit)** | LLM Agent 轨迹中"语义循环"的构念效度审计 |
| **[qt-skin-engine](https://github.com/Boris-boomer)** | Win32 进程注入 + CDP 的跨进程 UI 换肤引擎 |

---

#### 我在解决什么问题

现有 loop 检测系统都把"循环"等同于"重复"——动作参数不变、命令一样、返回值相同。但真实 Agent 会做另一种事：**每一步参数都不同、每次观测都是新的，可语义上就是卡在原地不动**。我 4 个月里主要在做两件事：

1. **工程侧**：把网页版 AI 变成可编程接口，把免费额度变成生产能力。
2. **研究侧**：量化"参数可变语义循环"在公开标注中的系统性缺失——这个构念目前既没有独立标注槽位，也没有和"精确重复"划清边界。

---

#### 技术栈

**语言**  Python · TypeScript · Rust · C · SQL

**AI / LLM**  DSPy · Ollama · vLLM · LLaMA-Factory · RAG · ChromaDB · MCP

**自动化**  Playwright · CDP · Win32 注入 · 浏览器逆向

**桌面 / 前端**  Tauri 2.0 · React 19 · PySide6 · Cordis · Tailwind CSS

**后端 / 数据**  FastAPI · asyncio · SQLite · uvicorn

**工具链**  uv · pnpm · tsdown · pytest · Vitest

---

#### 量化结果

- **8** 个自研 DSH 插件稳定运行于生产（icon-grid / loop-guard / mode-guard / CodeConstellation 等）
- **88** 个自动化测试全绿交付（Hermes-Browser）
- **29** 个功能模块 / 7 家 AI Provider / 中英双语（ShipSignal v1.2）
- **44.2%** 标注分歧率被量化，并定位到具体 48 个窗口（语义循环审计）

---

#### 工程信条

> 先侦察不猜 · 最小复现 · 单步闭环 · 跨项目对照 · 产物优先 · 运行时 > 静态源码

---

📬 **Email**　3090287415&#64;qq.com
🔗 **GitHub**　[github.com/Boris-boomer](https://github.com/Boris-boomer)
<!-- 🌐 **简历**　[boris-boomer.github.io](https://boris-boomer.github.io) -->
