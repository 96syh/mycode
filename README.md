# mycode

静态网页和前端小工具集合。目前主要包含两个 HTML 页面：一个 GitHub 文件夹上传工具，以及一个 Just Start AI 落地页原型。

## 当前内容

```text
.
├── github自动上传文件网页/
│   ├── github_uploader.html    # 浏览器端 GitHub 文件夹上传工具
│   └── juststartai.html        # Just Start AI 静态页面原型
└── read
```

## GitHub 文件夹上传工具

`github_uploader.html` 是一个纯前端工具，用于在浏览器中选择本地文件夹，并通过 GitHub API 上传到指定仓库。

特点：

- 不依赖后端服务。
- 使用浏览器文件选择能力读取本地文件。
- 需要用户提供 GitHub Personal Access Token。
- 适合少量文件或小型静态项目的手动上传。

安全注意：

- Token 只应在本地浏览器中临时使用。
- 不要把 Token 写入源码、截图、日志或公开仓库。
- 大文件、敏感文件和批量上传前建议先在测试仓库验证。

## Just Start AI 页面

`juststartai.html` 是一个静态落地页原型，内容面向 AI 与 trades/home services 场景。它可以作为页面视觉、文案结构或静态站点原型继续迭代。

## 使用方式

直接用浏览器打开对应 HTML 文件即可，无需构建步骤。

