## README

**提交内容**

1. ETL Scripts：数据获取、清洗、导入脚本
2. E-R Diagram：数据库模型E-R图、设计出的混合模型图以及最终的数据库表
3. Schema：MySQL的Schema定义文件
4. Warehouse Output File：MySQL的所有表导出的csv文件
5. Model Explain Document：混合模型选型原因和比较方案及结论
6. Hive Output File & Schema Difination：分布式文件系统导出文件，schema定义文件
7. Search & Statistics Programs：查询、展示程序
8. presentation PPT：答辩PPT

**环境及架构**

- 关系型数据库
  - OS：Ubuntu 14.04.1 LTS (GNU/Linux 3.13.0-32-generic x86_64)
  - Hardware：
    - CPU：Core i5 & RAM：2Gb
  - Database：MySQL 5.6.25 
  - Interface： JDBC
- 分布式文件型数据库
  - OS：Ubuntu 14.04.5 LTS (GNU/Linux 4.4.0-31-generic i686)  x3
  - Hardware：
    - CPU：Core i5 & RAM：4Gb  x1
    - CPU：Core i7 & RAM：4Gb  x2
  - Database：Hadoop 2.8.2 & Hive 2.1.1
  - Interface：JDBC
- 查询、展示程序
  - Database Driver：Mybatis & JDBC
  - Backend： Spring Boot
  - Frontend：Angular.js & HTML5

**成员贡献**

| 学号      | 姓名   | 贡献度(%) |
| ------- | ---- | ------ |
| 1552635 | 胡嘉鑫  | 25     |
| 1552672 | 吴可菲  | 25     |
| 1552673 | 陈明曦  | 25     |
| 1552674 | 李源   | 25     |

