# 项目

- 基于Spark的电影推荐系统



## 阶段1：项目体系架构概述

## 阶段2：基础环境搭建

- 虚拟机： virtualbox
- 系统：centos8
- 主机：localhost

配置Mongodb

配置redis

配置ElasticSearch

配置Azkaban 

配置Zookeeper

配置Spark

配置Kafka

配置Flume

## 阶段3：数据加载服务

- 模块：**DataLoader**
- 作用：
  - 将数据加载到MongoDB
  - 将数据加载到Elasticsearch

## 阶段4：推荐系统建设

- ### 统计推荐算模块

  - 模块：**StatisticsRecommender**
  - 实现：**Spark-SQL**

- ### 基于协同过滤的离线推荐模块

  - 算法：**ALS**
  - 模块：**OfflineRecommender**
  - 实现：**Spark-MLlib**
  
- ### 基于内容的推荐模块

  - 模块：**ContentRecommender**
  - 实现：**Spark-MLlib**

- ### 实时推荐模块

  - 模块：**StreamingRecommender**
  - 实现：**Spark- Streaming**

## 阶段5：前后端搭建

- 本部分不需要自己搭建，使用提供的 **businessServer** 即可







