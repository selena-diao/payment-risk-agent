# 支付风控审核Agent

基于Dify + Moonshot API构建的支付场景Agentic Workflow

## 架构
用户输入 → LLM初筛 → 条件路由 → Agent深度分析（黑名单+历史交易）→ 结构化风控报告

## 技术栈
- Dify Workflow
- Moonshot API (moonshot-v1-32k)
- FunctionCalling Agent策略
- 自定义工具：黑名单查询、历史交易分析

## 演示地址
https://udify.app/workflow/PfsAkuKoh5SjouAZ
## 运行截图
<img width="1504" height="817" alt="image" src="https://github.com/user-attachments/assets/e907a226-2166-4ef9-b15b-e669e4d0c48e" />
