# Java Spring Boot 开发可参考技能

基于代码库分析，以下技能可以用于Java Spring Boot开发：

## 🎯 适用于Java Spring Boot开发的技能

### 1. **claude-api** - Java SDK支持
- **路径**: `skills/claude-api/java/claude-api.md`
- **功能**: 提供Java SDK用于集成Claude API
- **用途**: 在Spring Boot应用中集成AI功能，包括：
  - 消息发送和流式响应
  - 工具使用（Tool Use）功能
  - 支持注解的工具类定义
  - 异步处理和响应式编程

### 2. **mcp-builder** - MCP服务器开发
- **路径**: `skills/mcp-builder/`
- **功能**: 构建MCP（Model Context Protocol）服务器
- **用途**: 为Spring Boot应用创建外部服务集成工具，包括：
  - API客户端封装
  - 错误处理和响应格式化
  - 分页支持
  - 工具注册和发现机制

### 3. **webapp-testing** - Web应用测试
- **路径**: `skills/webapp-testing/`
- **功能**: 使用Playwright进行Web应用测试
- **用途**: 测试Spring Boot Web应用的前端功能：
  - 自动化UI测试
  - 浏览器截图和日志捕获
  - 服务器生命周期管理
  - 前后端集成测试

### 4. **文档处理技能** - docx/pdf/pptx/xlsx
- **路径**: `skills/docx/`, `skills/pdf/`, `skills/pptx/`, `skills/xlsx/`
- **功能**: 文档生成和处理
- **用途**: Spring Boot应用中的文档处理功能：
  - 生成Word、PDF、PPT文档
  - 文档模板处理
  - 报告生成
  - Excel文件读写和数据报表生成

### 5. **skill-creator** - 技能创建工具
- **路径**: `skills/skill-creator/`
- **功能**: 创建和评估新技能
- **用途**: 开发自定义的Spring Boot开发工具和模板

## 🔧 推荐的技能组合

对于Java Spring Boot项目，建议重点关注：

1. **claude-api** - 集成AI功能
2. **mcp-builder** - 构建外部服务集成
3. **webapp-testing** - 自动化测试
4. **文档处理技能** - 根据需求选择docx/pdf/pptx/xlsx

这些技能可以帮助您构建现代化的Spring Boot应用，集成AI能力，实现自动化测试，并处理各种文档和数据格式。

## 📋 使用建议

- **新项目启动**: 先查看mcp-builder了解如何构建外部服务集成
- **AI功能集成**: 使用claude-api技能集成Claude AI功能
- **测试策略**: 利用webapp-testing进行端到端测试
- **文档需求**: 根据具体业务需求选择相应的文档处理技能