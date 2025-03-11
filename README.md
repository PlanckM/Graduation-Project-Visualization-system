# 毕业设计（论文）

## 感知通信定位一体化智能指挥决策服务平台

### 1. 项目背景
感知通信定位一体化智能指挥决策服务平台（以下简称**智能指挥决策服务平台**），研制任务来源于“十四五”国家重点研发计划项目子课题四“感知通信定位一体化指挥决策”。

本平台承载该重点研发项目多型装备应用验证及项目应用示范任务，构建“空天-水下”一体化全场景灾情感知指挥体系。

### 2. 可视化模型辅助决策子系统
**可视化模型辅助决策子系统**作为智能指挥决策服务平台的重要组成部分，主要实现灾场态势分析理解信息与辅助决策信息的可视化，为现场指挥员提供灾害场景的结构化信息及相匹配的预案或实现方案，帮助其做出合理的应急救援方案措施。

本系统主要利用**多源数据融合、机器学习、案例推演**等技术，结合**事件链、预案链、事故案例、专业知识**等信息，建立面向水上突发事件的**辅助决策知识模型**，分析事故特点、演化特征等内容，给出**风险防护、应急处置**等决策建议。

### 3. 系统主要功能
#### 3.1 典型知识库
- 提供各类典型案例、应急预案、法律法规等知识的调阅功能。
- 支持查看案例的图片、文档等各类资料信息。

#### 3.2 灾情分析
- 对各类灾情数据进行**多维度时空统计分析**。
- 采用**热力图、占比图**等统计图形进行灾害情景可视化展示。
- 进行**风险等级估计**，采用不同色块展示灾情严重程度。

#### 3.3 灾害链分析
- 利用灾害情境结构化要素的耦合关系，结合时间关系建立**灾害链路网络**。
- 以**二元结构图**的形式呈现灾害链。
- 支持**图形放大/缩小、图节点信息交互、灾害演化动态展示**等功能。

#### 3.4 知识推荐
- 以**灾害链图的主要特征**为基础，与**知识图中的应急预案、历史案例、法律法规**进行适应性匹配。
- 为指挥员提供**高置信度的推荐**及**自主条件匹配查询功能**。

---

以上内容概述了智能指挥决策服务平台及其可视化模型辅助决策子系统的核心内容及功能。