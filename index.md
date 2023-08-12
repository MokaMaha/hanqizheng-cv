---
layout: cv
title: HanQizheng
phone: 166-0025-5706
email:
  url: hanqizheng598@gmail.com
  text: hanqizheng598@gmail.com
---

# 韩启正

<!--
include contact information from the front matter
Supported arguments:
    - homepage: url, text
    - phone
    - email
-->

{% include cv-contact.html %}

## 基本信息
- 基本： 韩启正 &nbsp;\|&nbsp; 男 &nbsp;\|&nbsp; 1996
- 学历： 南开大学滨海学院 &nbsp;\|&nbsp; 本科 &nbsp;\|&nbsp; 计算机科学与技术 &nbsp;\|&nbsp; 2015.09 - 2019.06
- 博客：[https://hanqizheng.github.io](https://hanqizheng.github.io)

## 专业技能

- 熟悉 HTML5、CSS3、JavaScript、React 等前端基础。<br> 
- 熟悉 TypeScript。类型体操爱好者，可以熟练且规范地在日常生活中使用TS。<br>
- 了解 Node、Java。使用 Node 开发过中台项目，使用Java开发过后端接口。<br>
- 英语水平：CET-6。很喜欢英语，有良好的英文阅读、沟通能力。个人英文周边：[https://github.com/hanqizheng/Friends-Together](https://github.com/hanqizheng/Friends-Together)<br> 

## 工作经历

#### **北京希瑞亚斯科技有限公司（Moka）- 前端开发工程师** `2020.07 - 2023.08`

- 负责 Sugar Design (Moka的基础组件库) 的开发与维护
- 负责 Moka 低代码项目 ark 的开发
- 负责 Moka 元数据平台的开发与维护
- 负责 Moka People 薪酬、组织人事模块的业务开发与维护

#### **中发智能科技有限公司 - 前端开发工程师** `2019.06 - 2020.05`

- 负责公司业务需求开发，包含 PC 端、移动端
- 负责公司项目的维护和优化

## 项目经历

### **基础组件库 - Sugar Design**

> 技术栈：React \| TypeScript \| Next.js
<br> 

**项目描述：**<br> 
Sugar Design 是 Moka 的前端基础组件库。在全业务线中广泛应用。

**负责内容：**<br> 
- 项目owner。参与组件技术评审、代码CR、规范制定与推行、维护、oncall、迭代等日常工作。
- 组件开发。包括 Table(表格)、Layout(布局)、LineClamp(多行文本溢出)、Drawer(抽屉)等10+个组件。
- 项目优化。包括但不限于：
  - 项目按需加载配置优化、构建流程优化等。
  - 组件单测覆盖率优化。
  - 文档优化。包括文档易用性优化、文档内容修正走查、添加组件 props 说明文档自动生成功能。

**产生价值：**<br> 
- **独立开发 Table 并解决了 Moka 两大业务线中，因页面包含大数据量表格导致的性能问题**，目前 Table 已经在 Moka **全线产品的350+页面**中应用。Table技术说明: [https://hanqizheng.github.io/2021/11/28/NewTable.html](https://hanqizheng.github.io/2021/11/28/NewTable.html)
- 升级 Sugar 2.0大版本中 break changes 完成**100%平滑过渡**，业务线额外投入压缩至0.5pd/人。 Sugar 2.0 在 **Moka 全业务线替换完成**。
- 完善了共建规范、CR规范、发版规范、commit规范、change log规范等基建规范。扩大 Sugar Design 影响力。维护成本降低20%（通过发版耗时减少比例进行粗估）。

<br>

### **物料库 - Sweets**

> 技术栈：React \| TypeScript \| bit.js

**项目描述：**<br> 
Sweets 是 Moka 的前端物料库。物料是基于 Sugar Design 开发且内置务逻辑的组件。

**负责内容：**<br> 
- 物料准备。完成识别，搜集，汇总前端业务开发中已存在或潜在能提取为物料的内容。
- 物料开发。包括 ProfileHeader(Profile页头部)、JobPosition(职位)、BankCard(银行卡)、AddressSelector(地址)等组件。
- 物料平台基建完善。物料库答疑手册、业务共建流程等相关文档编写。CR、技术评审等规范制定。
- 日常工作。技术评审、代码 CR 和与业务侧同学对接等。

**产生价值：**<br> 
- 业务开发提效15%（组件开发耗时与应用次数粗估）。
- 统一业务侧对业务组件的使用口径。将分散在各个项目中的组件统一到物料库中，减少组件重复开发提高组件复用率。

### **元数据平台**

> 技术栈：React \| TypeScript \| Java 

**项目描述：**<br> 
元数据平台是 Moka 将多业务线所需字段统一管理的平台项目。

**负责内容：**<br>
- 参与前期方案调研、技术方案设计、技术评审等工作。
- 字段平台发布功能的导出功能的前后端开发工作。

**产生价值：**<br>
- 将多个业务线的字段注册统一管理，防止字段不统一，减少字段冲突。
- 提供导入导出的同步操作能力能够支持由模版设置无缝同步至租户设置能力，并且提供了字段的历史版本记录，方便租户进行字段的回滚操作。

### **CodeReview GPT**

> 技术栈：Node.js \| TypeScript \| LangChain \| GPT-3.5 API

**项目描述：**<br>
CodeReview GPT 是个人主导的AI探索项目，旨在通过 GPT-3.5 对业务测 code review 提效。<br>
相关博文：[https://hanqizheng.vercel.app/2023/07/27/code-review-gpt-workflow.html](https://hanqizheng.vercel.app/2023/07/27/code-review-gpt-workflow.html)

**负责内容：**<br>
- 项目owner。**独自**负责项目从设计到开发到维护的全过程。
- 技术透明化。定期向技术侧同学分享 CodeReviewGPT 相关的技术细节，使项目更加透明化，并且提高大家共建热情。

**产生价值：**<br>
- 提效研发侧效率10%(通过有效comment与CR时间进行的粗估)。对于代码规范中相对基础的问题都能够给出有效的建议，减少了CR的时间。

## 荣誉

- Moka优秀新人奖(2021)、Moka杰出个人奖(2022)、Moka面试官出类拔萃奖(2022)
