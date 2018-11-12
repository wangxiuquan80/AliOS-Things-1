## framework README.md模板

EN | [中文](./framework_template-zh.md)

framework README.md的模板可以参考[netmgr](../../framework/netmgr/README.md).

### 规范

文档应该简明扼要，只需要简单的说明即可，更具体的内容请引用外部的链接（github wiki，云栖博客等）。

#### 语言规范

文档**默认使用英文编写**，当然也可以中英文都支持，中文的文档名称为`README-zh.md`，跟英文文档`README.md`同一个目录，文档中按照如下方式建立中英文索引：

[EN](README.md) | [中文](README-zh.md)

#### 图片规范

为了防止文档过于复杂，**文档中不建议引用图片**，如果一定要引用图片的话，**请尽量引用外部链接**。

#### 文档内容规范

framework的README文档按照以下几种部分依次编写：

* 目录
* 介绍
* 需要条件（可选）
* API说明
* 如何使用
* 运行效果（可选）

### 介绍

**介绍**不做过多要求，建议按照如下几个部分介绍：

* 功能
* 依赖的组件(Dependent components)
* 补充说明

### 需要条件（可选）

**需要条件**该部分文档可选，主要说明该组件依赖什么硬件，需要适配过什么HAL层接口等，也可以引用外部链接。

### API说明

**API说明**主要说明一下API介绍，参考头文件等，请尽量引用外部链接。

### 如何使用

**如何使用**主要说明一下使用该组件需要在哪些地方加入代码，支持哪些CLI命令等。

### 运行效果（可选）

**运行效果**该部分文档可选，有必要的话，可以简单说明一下，或者引用外部链接。