# 美国客户现场部署英语作战包

创建时间：2026-05-12
适用场景：8 月美国出差，客户现场部署、技术交流、问题排查、会议确认。

## 核心目标

不是在 8 月前变成英语流利者，而是能完成客户现场技术交付：

1. 能用简单英语说明自己、项目、部署计划。
2. 能听出客户问题里的关键词。
3. 听不懂时敢于要求重复、放慢、打字或邮件确认。
4. 能围绕日志、配置、权限、网络、数据库、接口进行排查沟通。
5. 每次会议后能用英文邮件确认结论和 action items。

## 学习入口

- `daily-45min-plan.md`：每天 45 分钟固定训练法。
- `12-week-roadmap.md`：从 5 月中旬到 8 月的阶段计划。
- `survival-sentences.md`：现场保命句，优先背。
- `pronunciation-method.md`：不会发音时怎么练。
- `project-materials-todo.md`：需要你补充给发达的信息，用来生成你的专属部署材料。
- `agv-onsite-context.md`：已补充的 AGV 项目和现场背景。
- `agv-vocabulary-v1.md`：AGV / VDA5050 / Linux 内网部署高频词汇表。
- `agv-day1-practice.md`：基于 AGV 场景的第 1 天 45 分钟训练内容。
- `travel-life-phrasebook.md`：机场、坐飞机、入境、打车、酒店、餐厅等生活场景英语。
- `daily/`：每天一份 Markdown + HTML，HTML 用于打印携带练习。
- `templates/daily-print-template.html`：每日打印版 HTML 模板。

## 最重要原则

1. 先准备材料，再练口语。
2. 先练与你项目有关的句子，不泛泛背单词。
3. 所有关键结论都 written confirmation。
4. 听不懂绝不假装懂。
5. 用图、表格、checklist、日志、邮件降低纯口语压力。

## 每日启动口令

用户以后只需要说：

`开始英语学习`

发达会自动判断当前应该进入第几天，不需要用户手动说明 Day 几。

判断规则：

1. 先读取 `english-learning-state.json`。
2. 如果当天材料已生成但未完成，就继续当天。
3. 如果用户反馈已完成当天训练，就递增到下一天。
4. 每个新 Day 都生成一份 Markdown + 一份 HTML 打印版，保存在 `daily/`。
