---
tag: [coding, 协作, API]
author: bent
desc: 纯净的 API 交付说明
---

### 接口交付说明（给前端 Agent）

```
已经完成了后端接口开发，请根据以下契约完成集成：

1. **访问路径**：`[METHOD] [URL]`
2. **请求要求**：
   - **Authentication**: [如：需要 Bearer Token / 无]
   - **Headers**: [如：Content-Type: application/json]
   - **Parameters/Body**: [直接展示 JSON 结构或 Query Params]
3. **数据模型**：
   - 核心字段含义：[简述关键字段，如 id 是雪花 ID，status 是枚举]
4. **业务规则**：
   - 成功状态：[200/201 及其含义]
   - 异常路径：[哪些情况会报错，报错的 JSON 结构是什么样]
5. **集成建议**：
   - 这是一个 [同步/异步/长连接] 任务。
   - [可选：提供一个 cURL 示例，方便 Agent 验证]”
```
