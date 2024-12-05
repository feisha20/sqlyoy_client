# 贡献指南

感谢你考虑为 SQLyoy 项目做出贡献！

## 如何贡献

### 报告 Bug

1. 使用 GitHub Issues 提交 bug
2. 描述问题时请包含：
   - 操作系统版本
   - SQLyoy 版本
   - 问题复现步骤
   - 错误信息或截图

### 提交功能请求

1. 在提交新功能请求前，请先搜索现有的 issues
2. 使用 issue 模板描述你的功能建议
3. 说明这个功能可以解决什么问题

### 提交代码

1. Fork 项目仓库
2. 创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交你的修改 (`git commit -m '添加某个特性'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 创建一个 Pull Request

## 开发设置

1. 克隆项目
```bash
git clone https://github.com/你的用户名/SQLyoy.git
cd SQLyoy
```

2. 安装依赖
```bash
pip install -r requirements.txt
```

3. 运行测试
```bash
python -m pytest
```

## 代码规范

- 遵循 PEP 8 编码规范
- 所有新代码都需要添加适当的注释
- 提交信息要清晰描述改动内容

## Pull Request 规范

1. PR 标题要简洁明了
2. 描述��需要说明：
   - 改动的目的
   - 实现方式
   - 测试方法
3. 确保所有测试通过
4. 如果添加了新功能，请补充相应的文档

## 版本发布流程

1. 更新版本号
2. 更新 CHANGELOG.md
3. 创建新的 Release Tag
4. 编译并测试安装包
5. 发布新版本

感谢你的贡献！ 