

## ✅ 分类与比例设计

* **基础与SQL操作（20题）**
* **索引与性能优化（15题）**
* **事务与锁机制（15题）**
* **存储引擎与架构（10题）**
* **主从复制与高可用（10题）**
* **备份恢复与灾备（8题）**
* **性能调优与排障（10题）**
* **安全与权限管理（7题）**
* **运维自动化与监控（5题）**

---

## 🔹 一、基础与SQL操作（20题）

1. 说出 MySQL 支持的数据类型，并分别举例。
2. CHAR 和 VARCHAR 有什么区别？
3. TEXT 和 BLOB 的区别是什么？
4. DATE、DATETIME、TIMESTAMP 的区别？
5. ENUM 和 SET 的使用场景及区别？
6. LIMIT 的性能影响及优化方法？
7. COUNT(\*)、COUNT(1)、COUNT(列) 区别？
8. INNER JOIN、LEFT JOIN、RIGHT JOIN 区别及执行顺序？
9. UNION 和 UNION ALL 区别？
10. 子查询 vs JOIN，性能谁更好？为什么？
11. GROUP BY 和 DISTINCT 的区别？
12. WHERE 和 HAVING 区别？
13. MySQL 如何实现分页查询优化？
14. 如何在 SQL 中防止 SQL 注入？
15. 使用 CASE WHEN 在 SQL 中做条件处理的示例？
16. MySQL 的字符串函数有哪些？举例说明。
17. EXPLAIN 的作用是什么？能看到哪些信息？
18. JSON 字段在 MySQL 中的存储方式及查询方法？
19. SELECT FOR UPDATE 的作用？
20. 如何查询当前数据库的所有表和表结构？

---

## 🔹 二、索引与性能优化（15题）

21. 什么是聚簇索引和非聚簇索引？MySQL 中是哪种？
22. 什么是覆盖索引？有什么好处？
23. MySQL 索引失效的几种常见情况？
24. B+Tree 索引的结构特点？为什么不用 B-Tree？
25. HASH 索引适用于什么场景？
26. 如何选择合适的索引列顺序？
27. 什么是前缀索引？优缺点？
28. explain 中 type=ALL 表示什么？如何优化？
29. 什么是回表？如何避免？
30. 索引下推（Index Condition Pushdown）是什么？
31. InnoDB 的主键索引是如何存储的？
32. MySQL 多列索引的最左前缀原则是什么？
33. 为什么要尽量使用整型主键？
34. 复合索引和单列索引的性能差异？
35. 如何判断 SQL 使用了索引？

---

## 🔹 三、事务与锁机制（15题）

36. MySQL 的事务隔离级别有哪些？默认是哪种？
37. 每个隔离级别可能出现哪些问题？
38. InnoDB 如何实现 MVCC？
39. 什么是幻读？MySQL 如何避免幻读？
40. 什么是间隙锁（Gap Lock）？
41. 行锁和表锁的区别？MySQL 哪些引擎支持行锁？
42. 什么是意向锁？为什么要有意向锁？
43. 读写锁（S/X锁）的区别？
44. 如何查看当前有哪些事务和锁？
45. 死锁产生的原因？如何解决？
46. MySQL 的锁等待超时时间参数是什么？
47. 什么是 next-key lock？
48. 悲观锁和乐观锁区别？如何在 MySQL 中实现乐观锁？
49. 如何强制 MySQL 释放锁？
50. 分布式事务如何处理？两阶段提交和XA协议？

---

## 🔹 四、存储引擎与架构（10题）

51. MySQL 常见的存储引擎有哪些？区别？
52. MyISAM 和 InnoDB 区别？
53. MEMORY 引擎的特点？
54. InnoDB 的 redo log 和 undo log 有什么作用？
55. binlog、redo log、undo log 的区别与作用？
56. MySQL 的两阶段提交（2PC）是如何工作的？
57. InnoDB 如何保证崩溃恢复？
58. 为什么 InnoDB 支持事务而 MyISAM 不支持？
59. Explain 中 Extra 字段有哪些常见值？
60. 什么是 Buffer Pool？它的作用是什么？

---

## 🔹 五、主从复制与高可用（10题）

61. MySQL 主从复制的原理是什么？
62. 复制的三种模式（基于语句、基于行、混合）区别？
63. 延迟复制的场景和原理？
64. 如何判断主从延迟？
65. GTID 是什么？有什么优势？
66. 半同步复制和异步复制的区别？
67. 如何避免主从复制中的数据不一致？
68. MySQL MGR（Group Replication）的优缺点？
69. 高可用方案中，MySQL + Keepalived 的架构是怎样的？
70. 如何处理主库宕机？Failover 流程？

---

## 🔹 六、备份恢复与灾备（8题）

71. mysqldump 的原理及缺点？
72. xtrabackup 与 mysqldump 的区别？
73. 逻辑备份和物理备份区别？
74. 如何做热备份？
75. binlog point-in-time 恢复的流程？
76. 如何做全量备份+增量备份？
77. 如何快速恢复大数据库（>1TB）？
78. MySQL 如何防止误删数据？

---

## 🔹 七、性能调优与排障（10题）

79. MySQL 慢查询日志如何开启和分析？
80. 如何优化一个慢 SQL？
81. SHOW PROFILE 和 Performance Schema 的作用？
82. innodb\_buffer\_pool\_size 作用是什么？
83. MySQL 常见性能瓶颈有哪些？
84. 如何定位死锁？
85. Explain 输出中的 key\_len 字段表示什么？
86. 如何分析一个 SQL 是否需要优化？
87. SQL 优化中 join\_buffer\_size 的作用？
88. 当 QPS 激增时如何排查问题？

---

## 🔹 八、安全与权限管理（7题）

89. MySQL 用户认证机制是怎样的？
90. 如何创建只读用户？
91. 如何限制用户只能访问特定 IP？
92. 如何防止 SQL 注入？
93. MySQL 中 root 密码忘了怎么办？
94. 如何加密 MySQL 中的数据？
95. MySQL 8.0 的新安全特性有哪些？

---

## 🔹 九、运维自动化与监控（5题）

96. 如何使用 pt-query-digest 分析慢日志？
97. Prometheus + Grafana 如何监控 MySQL？
98. MySQL 常用健康检查指标有哪些？
99. 如何在不重启 MySQL 的情况下调整参数？
100. 如何实现 MySQL 在线 schema 变更？（gh-ost、pt-online-schema-change）

