# 智能BI

## 需求

1. 智能分析：用户输入目标和原始数据（图表类型），可以自动生成图表和分析结论
2. 图表管理
3. 图表生成的异步化（消息队列）
4. 对接AI能力

## 架构图

![image-20230620163116870](doc/image-20230620163116870.png)

## 准备使用技术栈

### 前端

1. React

2. Umi + Ant Design Pro
3. Echarts
4. umi openai 代码生成

### 后端

1. Spring Boot
2. MySql 
3. MyBatis Plus 数据访问框架
4. AI
5. Excel的上传和数据的解析
6. Swagger + Knife4j



## 2023-6-20

### 前端项目初始化

1. 去除国际化

### 后端项目初始化

1. 设计表结构,修改建表语句
2. 根据表结构创建mapper和service层代码
3. 去除无用代码
4. 逻辑删除
5. 生成编写对应的增删改查

### 明日计划

编写controller



