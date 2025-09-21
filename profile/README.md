[homepage](https://zeka-stack.github.io/#/)
# Zeka.Stack

<div align="center">

![Zeka.Stack Logo](https://raw.githubusercontent.com/zeka-stack/zeka.stack/main/supports/icons/icon.svg)

**一个现代化的企业级 Java 开发技术栈**

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen.svg)](https://spring.io/projects/spring-boot)
[![Java](https://img.shields.io/badge/Java-17+-orange.svg)](https://openjdk.java.net/)
[![Maven](https://img.shields.io/badge/Maven-3.6+-red.svg)](https://maven.apache.org/)

</div>

## 🌟 项目简介

Zeka.Stack 是一个基于 Spring Boot 3.x 和 Java 17+ 的现代化企业级开发技术栈，采用模块化设计理念，为 Java 开发者提供开箱即用的技术解决方案。项目名称 "Zeka" 寓意"智核"，体现了其作为智能开发核心的定位。

## 🏗️ 技术架构

Zeka.Stack 采用分层模块化架构，包含以下核心模块：

### 📦 核心模块

| 模块 | 名称 | 功能描述 | 状态 |
|------|------|----------|------|
| **arco-meta** | 架构元数据 | 项目构建管理框架，Maven 插件集合 | 🚀 活跃开发 |
| **blen-kernel** | 混合内核 | 企业级 Java 应用开发核心包 | 🚀 活跃开发 |
| **cubo-starter** | 立方启动器 | Spring Boot Starter 组件集合 | 🚀 活跃开发 |
| **domi-suite** | 领域套件 | 微服务领域组件集合 | 📋 规划中 |
| **eiko-orch** | 生态编排 | 基础设施编排组件 | 📋 规划中 |
| **felo-space** | 费洛空间 | 业务应用空间 | 📋 规划中 |

## 🚀 核心特性

### 🎯 现代化技术栈
- **Spring Boot 3.x** - 最新版本应用框架
- **Java 17+** - 现代化 Java 特性支持
- **Jakarta EE 9+** - 企业级规范支持
- **Maven 3.6+** - 现代化构建工具

### 🧩 模块化设计
- **按需引入** - 根据项目需求选择模块
- **独立部署** - 每个模块可独立使用
- **清晰边界** - 明确的模块职责划分

### 🛡️ 企业级功能
- **统一异常处理** - 全局异常处理机制
- **参数验证体系** - 完善的校验框架
- **代码生成工具** - 自动化代码生成
- **监控和追踪** - 完整的可观测性支持

### 🔧 开发友好
- **开箱即用** - 零配置即可使用
- **丰富文档** - 详细的文档和示例
- **约定大于配置** - 合理的默认配置
- **热更新支持** - 配置热更新能力

## 📚 快速开始

### 1. 引入核心依赖

```xml
<dependency>
    <groupId>dev.dong4j</groupId>
    <artifactId>blen-kernel</artifactId>
    <version>2.0.0-SNAPSHOT</version>
    <type>pom</type>
</dependency>
```

### 2. 使用 Starter 组件

```xml
<dependency>
    <groupId>dev.dong4j</groupId>
    <artifactId>cubo-ssm-spring-boot-starter</artifactId>
    <version>2.0.0-SNAPSHOT</version>
</dependency>
```

### 3. 创建应用

```java
@SpringBootApplication
public class Application {
    public static void main(String[] args) {
        SpringApplication.run(Application.class, args);
    }
}
```

## 🎨 设计理念

### 命名规范
- **Arco**: Architecture + Core，适合架构主模块
- **Blen**: Blend，混合、集成，适合工具模块
- **Cubo**: Cube 的变体，结构性强，通用工具模块
- **Domi**: Domain + Microservice，领域微服务集合
- **Eiko**: 拟造词，音似 eco（生态），技术基座感
- **Felo**: Framework + Logic，现代感框架逻辑
- **Zeka**: 自造词，音近"智核"，个性强、易注册品牌

### 核心原则
- **约定大于配置** - 提供合理的默认配置
- **模块化设计** - 清晰的模块边界和职责
- **企业级特性** - 完整的生产环境支持
- **开发效率** - 提升开发体验和效率

## 📖 文档资源

- 📚 [项目文档](https://zeka-stack.github.io/)
- 🚀 [快速开始指南](https://zeka-stack.github.io/docs/getting-started/)
- 🔧 [API 参考](https://zeka-stack.github.io/docs/api/)
- 💡 [最佳实践](https://zeka-stack.github.io/docs/best-practices/)

## 🤝 贡献指南

我们欢迎所有形式的贡献！

- 🐛 **问题报告** - 发现 Bug 请及时反馈
- 💡 **功能建议** - 提出新功能想法
- 🔧 **代码贡献** - 提交代码改进
- 📖 **文档改进** - 完善项目文档

### 开发环境设置

```bash
# 克隆项目
git clone https://github.com/zeka-stack/zeka.stack.git
cd zeka.stack

# 构建项目
mvn clean install

# 运行测试
mvn test
```

## 📄 许可证

本项目采用 [MIT License](LICENSE) 许可证。

## 📞 联系方式

- **作者**: dong4j
- **邮箱**: dong4j@gmail.com
- **项目地址**: https://github.com/zeka-stack/zeka.stack
- **问题反馈**: https://github.com/zeka-stack/zeka.stack/issues

## 🙏 致谢

感谢所有为 Zeka.Stack 项目做出贡献的开发者们！

---

<div align="center">

**Zeka.Stack** - 让 Java 开发更简单、更高效、更智能！

[⭐ Star](https://github.com/zeka-stack/zeka.stack) • [🐛 Issues](https://github.com/zeka-stack/zeka.stack/issues) • [📖 Docs](https://zeka-stack.github.io/) • [💬 Discussions](https://github.com/zeka-stack/zeka.stack/discussions)

</div>