---
sidebar_position: 5
title: 0.6.0 release
---

| 版本   | 二进制程序                                                                                                                | Source                                                                               |
|-------|----------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|
| 0.6.0 | [dlink-release-0.6.0.tar.gz](https://github.com/DataLinkDC/dlink/releases/download/0.6.0/dlink-release-0.6.0.tar.gz) | [Source code (zip)](https://github.com/DataLinkDC/dlink/archive/refs/tags/0.6.0.zip) |


## Dinky发行说明

Dinky 0.6.0 是一个新功能版本，主要包括运维中心。

### 新功能

- 新增作业目录树关键字搜索框
- 新增 F2 全屏开发
- 新增 K8S 集群配置
- 新增 Doris 数据源注册、元数据、查询和执行
- 新增 SqlServer 数据源注册、元数据、查询和执行
- 新增 Oracle 数据源注册、元数据、查询和执行
- 新增 Phoenix 数据源注册、元数据、查询和执行
- 新增 Hive 数据源注册、元数据、查询和执行
- 新增元数据生成 FlinkSQL 和 SQL
- 新增 CDCSOURCE 多源合并任务语法支持
- 新增作业生命周期管理
- 新增 FlinkJar Dialect 的管理
- 新增 Batch 引擎
- 新增数据源的连接信息片段机制自动注入
- 新增用户密码修改
- 新增报警模块（实例和组）
- 新增钉钉报警
- 新增微信企业号报警
- 新增运维中心任务实例功能
- 新增运维中心任务实时监控功能
- 新增运维中心任务监控的 FlinkWebUI、智能停止、SavePoint 等操作
- 新增运维中心任务监控的作业总览
- 新增运维中心任务监控的配置信息
- 新增运维中心任务监控的智能重启和报警推送
- 新增实时自动告警
- 新增 Application 模式自增修正 checkpoint 和 savepoint 存储路径
- 新增作业发布时进行语法校验和逻辑检查
- 新增作业上下线自动提交和停止任务
- 新增作业生命周期与任务实例同步联动
- 新增运维中心的作业实例与历史切换
- 新增运维中心的异常信息实现
- 新增运维中心的 FlinkSQL 实现
- 新增运维中心的报警记录实现
- 新增运维中心血缘分析——字段级
- 新增作业剪切和粘贴
- 新增实时任务监控容错机制

### 修复和优化

- 升级 SpringBoot 至 2.6.3
- 升级 Flink 1.13.5 至 1.13.6
- 优化 sql 美化
- 优化默认启用数据预览等
- 修复前端 state 赋值 bug
- 修复异常预览内容溢出 bug
- 修复数据预览特殊条件下无法获取数据的 bug
- 优化 SQL 编辑器性能
- 修复全屏开发退出后 sql 不同步
- 优化作业配置查看及全屏开发按钮
- 优化异常日志的捕获、反馈与持久化
- 优化元数据数据源的的类型转换和连接管理
- 优化 K8S Application 提交配置
- 优化 PerJob 和 Application 作业的 JID 提交检测
- 修复集群配置参数项为空时无法正常提交 perjob 任务的bug
- 优化语法检测建议的结果提示
- 修复 Oracle 无法正确获取元数据的 bug
- 修复报警组刷新当前页面时无法正常显示下拉报警实例
- 优化当提交作业无法获取 JID 时变为提交失败
- 优化 IDEA 调试时的依赖配置
- 修复用户未登录时后台报错及鉴权问题
- 修复用户逻辑删除 bug
- 修复 kubernetes 集群配置相关显示 bug
- 优化 Studio 血缘分析为字段级
- 修复 Doris 无法获取到列的主键信息
