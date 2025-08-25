# 基于比特承诺模型的去中心化投票系统

> 🎯 **项目主页** - 欢迎来到去中心化决策投票系统的官方主页

## 📖 项目简介

本项目是一个基于比特承诺模型的去中心化决策投票系统，结合Rust WebAssembly高性能计算与区块链技术的不可篡改特性，支持大规模决策场景。系统通过密码学技术确保决策人偏好投票的隐私性，利用区块链保证数据完整性，实现真正去中心化的决策机制。

### 🎯 核心特性

- **🔐 隐私保护**：使用比特承诺协议保护投票内容不被泄露
- **⚡ 高性能**：基于Rust WebAssembly的高性能计算引擎
- **🔗 去中心化**：基于Injective区块链平台，确保数据不可篡改
- **✅ 可验证性**：所有决策结果透明可验证
- **🎨 NFT化**：通过NFT管理投票资格和项目属性
- **🪙 代币权限**：基于$LUCKEE代币的权限控制系统

## 🚀 应用场景

### 1. 去中心化抽奖
- **功能**：支持n选1、n选k的公平抽奖
- **特点**：每个参与者的随机数都会影响最终结果
- **流程**：NFT分发 → 提交随机数 → 隐私保护 → 结果计算 → 验证

### 2. 去中心化彩票
- **功能**：基于集体偏好的彩票系统
- **特点**：透明开奖，自动分配奖金
- **状态**：后续迭代支持

### 3. 去中心化分配
- **功能**：基于偏好的资源分配系统
- **特点**：公平分配，自动执行
- **状态**：后续迭代支持

### 4. 去中心化治理投票
- **功能**：社区治理决策投票
- **特点**：隐私保护，结果可验证
- **状态**：后续迭代支持

## 🛠️ 技术架构

### 核心技术栈
- **区块链平台**：Injective (CosmWasm生态)
- **智能合约**：Rust + CosmWasm
- **高性能计算**：Rust WebAssembly
- **存储方案**：IPFS + 链上摘要
- **前端技术**：现代Web技术栈

### 系统组件
```
src/
├── contracts/     # 智能合约代码
├── frontend/      # 前端界面
├── home/          # 项目主页 (当前目录)
├── ipfs/          # IPFS存储相关
├── sdk/           # 开发工具包
├── server/        # 服务器端逻辑
└── wasm/          # WebAssembly模块
```

## 🎮 快速开始

### 环境要求
- Node.js 16+
- Rust 1.70+
- Injective CLI
- IPFS节点

### 安装步骤

1. **克隆项目**
```bash
git clone <repository-url>
cd 去中心化彩票
```

2. **安装依赖**
```bash
# 安装Rust依赖
cargo build

# 安装前端依赖
cd src/frontend
npm install
```

3. **配置环境**
```bash
# 复制环境配置文件
cp .env.example .env
# 编辑配置文件
```

4. **启动开发环境**
```bash
# 启动智能合约
cd src/contracts
cargo wasm

# 启动前端服务
cd src/frontend
npm run dev
```

## 📚 文档导航

### 设计文档
- [项目总览](../../doc/项目总览.md) - 项目完整概述
- [需求说明书](../../doc/需求说明书.md) - 详细功能需求
- [技术白皮书](../../doc/技术白皮书.md) - 技术实现方案
- [概要设计说明书](../../doc/概要设计说明书.md) - 系统架构设计
- [详细设计说明书](../../doc/详细设计说明书.md) - 详细技术设计

### 技术选型
- [Rust智能合约开发指南](../../doc/技术选型/Rust智能合约开发指南.md)
- [IPFS存储策略设计说明书](../../doc/技术选型/IPFS存储策略设计说明书.md)
- [iAgent自动化功能设计说明书](../../doc/技术选型/iAgent自动化功能设计说明书.md)
- [多应用场景支持设计说明书](../../doc/技术选型/多应用场景支持设计说明书.md)
- [多目标选择技术实现方案](../../doc/技术选型/多目标选择技术实现方案.md)

### 其他文档
- [可行性分析报告](../../doc/可行性分析报告.md)
- [项目术语表](../../doc/项目术语表.md)

## 🔧 开发指南

### 智能合约开发
```bash
cd src/contracts
cargo test
cargo wasm
```

### 前端开发
```bash
cd src/frontend
npm run dev
npm run build
```

### WebAssembly开发
```bash
cd src/wasm
cargo build --target wasm32-unknown-unknown
```

## 🤝 贡献指南

我们欢迎社区贡献！请遵循以下步骤：

1. Fork项目
2. 创建功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启Pull Request

### 开发规范
- 遵循Rust编码规范
- 编写完整的测试用例
- 更新相关文档
- 确保代码通过CI检查

## 📄 许可证

本项目采用MIT许可证 - 查看 [LICENSE](../../LICENSE) 文件了解详情。

## 📞 联系我们

- **项目主页**：[GitHub Repository](https://github.com/your-repo)
- **问题反馈**：[Issues](https://github.com/your-repo/issues)
- **讨论区**：[Discussions](https://github.com/your-repo/discussions)

## 🗺️ 项目路线图

### Phase 1 (当前阶段)
- ✅ 基础架构搭建
- ✅ 比特承诺协议实现
- ✅ NFT管理系统
- ✅ 去中心化抽奖功能
- 🔄 多目标选择算法
- 🔄 iAgent自动化功能

### Phase 2 (后续迭代)
- 📋 去中心化彩票系统
- 📋 去中心化分配系统
- 📋 去中心化治理投票
- 📋 跨链功能支持

---

> 💡 **提示**：如果您是第一次访问，建议先阅读[项目总览](../../doc/项目总览.md)了解项目全貌，然后查看[需求说明书](../../doc/需求说明书.md)了解具体功能需求。
