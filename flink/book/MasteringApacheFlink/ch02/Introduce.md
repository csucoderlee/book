# 本章介绍

## 标题 Data Processing Using the DataStream API

使用流处理来处理数据

## 章节介绍

实时处理是一个重要的课题。许多不同的工程领域都需要实时处理数据。

目前已经有很多技术提供实时处理的功能，比如说Storm和spark。

物联网IoT驱动的应用程序需要实时的去存储、处理和分析数据。

为了满足这些场景，Flink提供了流处理api - dataStream api。

在本节，我们从一下方面来学习流处理api
- 执行环境 Execution environment
- 数据源 data sources
- 转化器    Transformations
-      Data sinks
-      connectors
- 真实案例 - 传感器数据分析 sensor data analytics

任何一个flink的程序都可以分解为一下几个步骤

obtain execution environment
load data from source
transform data
transform data
store the processed data

