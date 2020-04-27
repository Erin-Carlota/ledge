# 重构智库

基于：[系统重构与迁移指南](https://github.com/phodal/migration)

# 为什么重构？

## 重构的动机

## 重构不一定能带来什么？

## 重构是一种文化

## 大规模重构的时机

## 说清重构的价值

# 系统重构模式与原则

## 重构模式：IPDCA

## 四级重构

## 小步前进

## Git 工作流

- Master 机制
- PR 机制

# 建立远景与方向

## 拉通：对齐目标

## 明确潜在风险

## 人评估

## 重构范围

## 产出物

- KPI 度量
- 重建规范
- 团队赋能
- 原则与模式

# 重构评估与度量

## 识别技术债务

- 技术债风暴
- 架构评估：技术驱动 vs 业务驱动
- 代码评估：收集 bad smell
- 收集 Todo
- 测试和文档评估

## 项目评估

## 编写工具评估

## 代码评估工具

## 真实的测试覆盖率

## 可测试性评估

## 度量

## 寻找专业人士

# 重构准入条件

## 工具准备

## 重构看板

## 版本控制

## 自动化重构工具

## 持续集成环境

## 记录

# 探索性重构：可行方案

## 准备知识：坏味道的模式

- C4 模型

## 探索模式

- 1. 从分层架构到具体代码
- 2. 从外部适配器到内部适配器
- 3. 查看测试情况
- 4. 针对于最复杂的情形和最简单的情形
- 工具：API 列表和调用关系

## 构建领域知识

- 了解业务架构
- 架构全景
- 领域名词表

## 寻找高引用 + 高修改

# 第一步：防护网

## 防护网策略

## 第一个测试

## 持续集成重构

## 检视测试

# 系统架构重构

## 高质量级 DDD 重构：演进驱动的事件风暴

## 轻量级 DDD 重构：现状驱动的领域方案

## 限界上下文要素

## 微服务重构

# 服务架构重构

## 整洁架构

## 设计新架构

## 实施新分层架构

- 划分类，移动代码
- 技术模块化 => 重搭

## 中间态分层

## 验收条件：构建

## 潜在问题

- bean 注入
- 解决冲突
- 同步 API 修改
- 对齐新分层架构

# 公共代码重构

## 它真是个 util 吗？

## 过度设计

## 重新定义：消除二义性

## 类进行内聚

## 划分技术部分

## 划分业务部分

- 职责少 => 平级
- 业务代码多 => 再按业务拆分

# 模块重构

## 组件聚合三原则

## 打破包之间的依赖关系

## 依赖倒置

- 更好的面向对象

## 清理垃圾代码

# 模型重构

## 聚合行为

- 由内到外剥离，由外到内聚合
- 识别模式 1：输入参数
- 识别模式 2：返回参数
- 优化创建

## 重命名：统一语言

- 类
- 状态
- 方法
- 容器

## 离心分离模型：消除二义性

## 提取参数对象

## 处理过程逻辑

## 领域特定语言

# 模式重构

## 终止 Singleton

## 工厂封装复杂构建

- 重构手法

## 策略模式提供易变规则

## 建造者模式拆解复杂对象

## 工具：自动化识别

# 代码重构

## 降低圈复杂度

## 手法：提取

## 手法：内联

## 手法：移动

- 方法移至其它类中

## 标准：4 行的方法

# 重构示例

## 评估

- C4 模型展开

## 工具评估

- 代码统计
- 基本情况评估
- 代码坏味道评估
- 架构评估
- API 评估
- API 架构图
- 高引用 + 高修改分析
- 没有测试

## 重构策略

## 架构重构

## 分层重构

## 模型重构

## 代码重构

# 自动化重构

# 数据库重构（TBC）

## 数据库回归测试：数据不变性

- 前测试
- 后测试

## 引入数据库迁移工具

## 迁移源数据

## 汲取式重构：存储过程转换

# 重构之后：工具的问题

## 架构守护

- 架构守护测试
- 坏味道守护

## 测试驱动开发

## 完善基础设施

# 重构之后：解决人的问题

## 代码写得烂

## 养成优秀的开发习惯

## 人员能力提升

- 练习项目
- 培训教程
- 典型问题

# 重构之后：流程的问题

## 流程优化

## 需求规范化

- 实例化需求
- 行为驱动开发（BDD）

# 重构之后：提炼知识

## 知识仓库

## 重建知识仓库

# 问题是什么？

## 为什么我们需要重构？

# 重构到微服务

# 未来

## 追求技术卓越。

## 推动个人变革，进而引领组织变革

## 整理知识，加强教育

## 在整个流程中将价值创造最大化