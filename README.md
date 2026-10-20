# hello-world

> 我的第一个 GitHub 仓库：练手与实验

一个用来熟悉 GitHub 各项功能（Issue、Actions、Pages、Release）的沙盒仓库。
内容会随实验不断变化，不保证稳定性。

## 目录结构

```
.
├── README.md              项目说明
└── .github/
    └── ISSUE_TEMPLATE/    Issue 模板
        ├── bug_report.md
        └── feature_request.md
```

## 快速开始

```bash
git clone https://github.com/puyu-l/hello-world.git
cd hello-world
```

## 待办

- [x] 创建仓库
- [x] 配置 Issue 模板
- [ ] 尝试 GitHub Actions 自动检查
- [ ] 开启 GitHub Pages 发布静态页
- [ ] 打第一个 Release

## 注意事项

本仓库为**公开**状态，任何人都能看到提交历史。

提交前确认文件里没有：

- API key、访问令牌、私钥
- 数据库密码、连接串
- 内网地址、公司内部信息

一旦提交并推送到公开仓库，即使后续删除，内容也可能已被爬虫抓取。
这类文件请放到私有仓库，或通过 `.gitignore` 排除。
