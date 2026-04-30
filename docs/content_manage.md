# 内容管理

## 1. 文档格式

使用Markdown格式编写文档。

metadata 需要包含以下字段：

- layout: document
- title: 文档标题
- date: 文档日期
- area: 影响区域
- excerpt: 文档摘要

例如：

```markdown
---
layout: document
title: 2026年第2次业主大会公告
date: 2026-04-29
area: 全区域
excerpt: 定于2026年?月?日召开2026年第2次业主大会，会议议题：1. 是否同意解聘原物业服务企业（金迪）, 2. 是否同意授权由5名业主代表组成临时选聘工作小组。
---
。。。
```

## 2. 文档位置

- 公告文档需要放在`_announcements`目录下，文件名需要以日期开头，例如`20260429-meeting-announce-02.md`。
- 决策文档需要放在`_decisions`目录下，文件名需要以日期开头，例如`20260429-decision-02.md`。
- 规章文档需要放在`_rules`目录下，文件名需要以`rule`前缀开头，例如`rule001_name.md`。
- 财务文档需要放在`_finance`目录下，文件名需要以日期开头，例如`20260429_name.md`。
- 项目文档需要放在`_projects`目录下，文件名需要以日期开头，例如`20260429_name.md`。