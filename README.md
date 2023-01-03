# blog-comments

## 博客评论仓库
目前使用的是 `giscus`，由 GitHub Discussions 驱动的评论系统。让访客借助 GitHub 在你的网站上留下评论和反应吧！本项目受 utterances 强烈启发。

文档地址：https://giscus.app/zh-CN

## 它如何运作
giscus 加载时，会使用 GitHub Discussions 搜索 API 根据选定的映射方式（如 URL、pathname、<title> 等）来查找与当前页面关联的 discussion。如果找不到匹配的 discussion，giscus bot 就会在第一次有人留下评论或回应时自动创建一个 discussion。

要评论，访客必须按 GitHub OAuth 流程授权 giscus app 代表他发帖。或者访客也可以直接在 GitHub Discussion 里评论。你可以在 GitHub 上管理评论。
