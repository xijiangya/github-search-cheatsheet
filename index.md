---
layout: default
title: GitHub 搜索筛选符号速查表
---

# GitHub 搜索筛选符号速查表

---

## 📌 基础筛选

| 符号 | 示例 | 说明 |
|------|------|------|
| `in:name` | `react in:name` | 仓库名包含关键词 |
| `in:description` | `chat bot in:description` | 描述包含关键词 |
| `in:readme` | `AI assistant in:readme` | README 中包含关键词 |
| `in:topic` | `machine-learning in:topic` | 话题标签包含关键词 |

## ⭐ 热度筛选

| 符号 | 示例 | 说明 |
|------|------|------|
| `stars:>n` | `stars:>1000` | 星标大于 1000 |
| `stars:n..m` | `stars:100..500` | 星标在 100-500 之间 |
| `stars:>=n` | `stars:>=5000` | 星标大于等于 5000 |
| `forks:>n` | `forks:>500` | Fork 数大于 500 |

## 📅 时间筛选

| 符号 | 示例 | 说明 |
|------|------|------|
| `created:>YYYY-MM-DD` | `created:>2024-01-01` | 某日期后创建 |
| `created:<YYYY-MM-DD` | `created:<2024-06-01` | 某日期前创建 |
| `pushed:>YYYY-MM-DD` | `pushed:>2024-06-01` | 某日期后有更新 |
| `pushed:<YYYY-MM-DD` | `pushed:<2023-01-01` | 某日期后未更新（可能已弃用） |

## 🔤 语言筛选

| 符号 | 示例 | 说明 |
|------|------|------|
| `language:python` | `language:python` | Python 项目 |
| `language:javascript` | `language:javascript` | JavaScript 项目 |
| `language:go` | `language:go` | Go 项目 |

## 📋 仓库状态

| 符号 | 示例 | 说明 |
|------|------|------|
| `archived:true` | `vue archived:true` | 已归档（不再维护） |
| `archived:false` | `react archived:false` | 未归档（仍在维护） |
| `mirror:true` | `linux mirror:true` | 镜像仓库 |
| `template:true` | `vue template:true` | 模板仓库 |
| `private:true` | `private:true` | 私有仓库 |
| `public:true` | `public:true` | 公开仓库 |
| `fork:true/false` | `fork:false` | 排除/只看 Fork |

## 👤 用户 & 组织

| 符号 | 示例 | 说明 |
|------|------|------|
| `user:xxx` | `user:microsoft` | 某用户/组织的仓库 |
| `org:xxx` | `org:facebook` | 某组织的仓库 |
| `followers:>n` | `followers:>100` | 关注者大于 100（搜用户时用） |

## 📂 仓库大小

| 符号 | 示例 | 说明 |
|------|------|------|
| `size:>n` | `size:>10000` | 大于 10MB（单位 KB） |
| `size:n..m` | `size:100..1000` | 大小在范围内 |

## 🏷️ 话题 & 许可证

| 符号 | 示例 | 说明 |
|------|------|------|
| `topic:xxx` | `topic:deep-learning` | 某话题标签 |
| `license:mit` | `license:mit` | MIT 许可证 |
| `license:apache-2.0` | `license:apache-2.0` | Apache 2.0 |

## 🔧 Issues 搜索

| 符号 | 示例 | 说明 |
|------|------|------|
| `is:issue` | `is:issue is:open` | 只看 Issue |
| `is:pr` | `is:pr is:merged` | 只看已合并的 PR |
| `label:xxx` | `label:bug` | 某标签的 Issue |
| `author:xxx` | `author:torvalds` | 某人提交的 |
| `assignee:xxx` | `assignee:octocat` | 分配给某人 |
| `is:open` | `is:open` | 开放的 |
| `is:closed` | `is:closed` | 已关闭的 |
| `comments:>n` | `comments:>10` | 评论大于 10 条 |
| `sort:created-desc` | `sort:updated-desc` | 按创建/更新时间倒序 |

## 🔧 Code 搜索

| 符号 | 示例 | 说明 |
|------|------|------|
| `path:xxx` | `println path:src` | 限定文件路径 |
| `extension:xxx` | `fetch extension:py` | 限定文件扩展名 |
| `filename:xxx` | `filename:config` | 限定文件名 |

---

## 🔥 实用组合示例
