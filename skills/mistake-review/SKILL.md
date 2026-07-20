---
name: mistake-review
description: 当用户要求对某个测验进行批改时，对用户的回答进行批改和解析
---

# Quiz Answer Reviewer

## 什么时候使用？

当用户明确要求对某个测验进行批改时，使用此技能

## 怎么用？

读取用户提供的测验答题记录文件：Unit-X-Quiz-XX-Answers.md 和同目录下的 Quiz 文件：Unit-X-Quiz-XX.md，对每道题进行批改和解析，将批改结果和总体分析附到 Unit-X-Quiz-XX-Answers.md 文档末尾的 ##作答批改 部分中

说明：
  - Unit-X-Quiz-XX-Answers.md 文件中包含用户的原始答案、自我批改以及掌握反馈