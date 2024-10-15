---
created: 2024-10-09T11:01:53 (UTC +08:00)
tags: []
source: https://mp.weixin.qq.com/s/MIobySHXfzr-Adb5d8hpEQ
author: RUNOOB
---

# SQL 速成手册，收藏不学习系列

> ## Excerpt
> 

---
SQL（Structured Query Language，结构化查询语言）是一种用于管理和操作关系型数据库的标准化编程语言。

![图片](https://mmbiz.qpic.cn/mmbiz_png/vqlbVFl5Jn1k4XasuAae1vxS7E5VZztkptiayyOniasoe2ZoEibqZzceAVib2nslgBPicuMjUnuibbNAzkd2poTtp2HQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

SQL 被广泛用于数据库系统中（如 MySQL、PostgreSQL、Oracle、SQL Server），用于执行查询、更新数据、管理数据库结构和控制数据库访问权限。

![图片](https://mmbiz.qpic.cn/mmbiz_jpg/vqlbVFl5Jn1k4XasuAae1vxS7E5VZztkIspyIWUiceKGPLjmD72lic5xh2OTpLD18150nyCRBsz9rwCgqdmkGGkA/640?wx_fmt=webp&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

**SQL 的主要功能**

![图片](https://mmbiz.qpic.cn/mmbiz_png/vqlbVFl5Jn1k4XasuAae1vxS7E5VZztkCia81pjibu10c9XEAxcp6Gn3ehmfsy6eR9ln54zynfVV7JZEVCicysuNg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

**1、基本查询语句**

-   SELECT - 用于从数据库中选择数据，返回结果集。
    
-   WHERE - 用于过滤记录，指定查询条件。
    
-   ORDER BY - 用于对结果集进行排序，可以按升序或降序排列。
    
-   DISTINCT - 用于返回唯一不同的值，去除重复记录。
    
-   LIMIT - 用于指定返回的记录数量，常用于分页。
    

**2、表操作语句**

-   CREATE TABLE - 用于创建新表，定义表的列和数据类型。
    
-   ALTER TABLE - 用于修改现有表的结构，例如添加、删除或修改列。
    
-   DROP TABLE - 用于删除表及其所有数据。
    

**3、数据操作语句**

-   INSERT INTO - 用于向表中插入新记录。
    
-   UPDATE - 用于修改表中的现有记录。
    
-   DELETE - 用于删除表中的记录。
    

**4、函数与聚合操作**

-   COUNT - 用于返回匹配条件的行数。
    
-   SUM - 用于返回列的总和。
    
-   AVG - 用于返回列的平均值。
    
-   MIN - 用于返回列的最小值。
    
-   MAX - 用于返回列的最大值。
    

**5、子查询与联接**

-   INNER JOIN - 用于返回两个表中都存在的匹配记录。
    
-   LEFT JOIN - 用于返回左表中的所有记录和右表中的匹配记录。
    
-   RIGHT JOIN - 用于返回右表中的所有记录和左表中的匹配记录。
    
-   FULL JOIN - 用于返回两个表中所有记录，不管是否匹配。
    
-   SUBQUERY - 用于在查询语句中嵌套另一个查询。
    

**6、高级操作**

-   UNION - 用于合并两个或多个 SELECT 语句的结果集。
    
-   CASE - 用于实现条件逻辑，返回不同的值。
    
-   INDEX - 用于创建索引以加速查询。
    

**7、性能优化与安全性**

-   EXPLAIN - 用于查看查询的执行计划，帮助优化查询。
    
-   TRANSACTION - 用于处理事务，确保数据的一致性和完整性。
    
-   GRANT - 用于授予用户特定的数据库权限。
    
-   REVOKE - 用于撤销用户的数据库权限。
    

___

**一、基本查询语句**

**SELECT**：用于从数据库中选择数据。

```
<span><span>SELECT</span> column1, column2 <span>FROM</span> table_name;</span>
```

column1, column2 表示列名，table\_name 表示表名。

**WHERE**：用于过滤记录。

```
<span><span>SELECT</span>&nbsp;column1,&nbsp;column2&nbsp;<span>FROM</span>&nbsp;table_name&nbsp;<span>WHERE</span>&nbsp;condition;</span>
```

**ORDER BY**：用于排序结果集。  

```
<span><span>SELECT</span> column1, column2 <span>FROM</span> table_name </span>
```

-   **ASC（Ascending）**：表示升序排序，即从小到大排列（默认排序方式）。
    
-   **DESC（Descending）**：表示降序排序，即从大到小排列。
    

**DISTINCT**：用于返回唯一不同的值。  

```
<span><span>SELECT</span> <span>DISTINCT</span> column1 <span>FROM</span> table_name;</span>
```

**LIMIT**：用于指定返回的记录数量。  

```
<span><span>SELECT</span> column1 <span>FROM</span> table_name <span>LIMIT</span> <span>number</span>;</span>
```

**二、表操作语句**  

**CREATE TABLE**：用于创建新表。

```
<span><span>CREATE</span> <span>TABLE table_name (</span></span>
```

-   **column1, column2, column3：**表的列名。
    
-   **datatype：**这列的数据类型，比如INT表示整数，VARCHAR(255)表示最大长度为255的字符串等。
    
-   **PRIMARY KEY：**这是一个约束，用来指定哪列是主键。主键是表中用来唯一标识每行数据的列。在上面的例子中，column1 被指定为主键。
    

**ALTER TABLE**：用于修改现有表结构。

```
<span><span>-- 向 table_name 表添加名为 column_name 的新列，数据类型为 datatype</span></span>
```

**DROP TABLE**：用于删除表。

```
<span><span>DROP</span> <span>TABLE</span> table_name;</span>
```

**三、数据操作语句**  

**INSERT INTO：**用于向表中插入数据。

```
<span><span>INSERT</span> <span>INTO</span> table_name (column1, column2) <span>VALUES</span> (value1, value2);</span>
```

这个语句将向 table\_name 表中插入一行数据，其中 column1 列的值设为 value1，column2 列的值设为 value2。  

如果列名列表中包含表中的所有列，则不需要指定列名，可以直接使用**INSERT INTO table\_name VALUES (...);** 的语法。

**UPDATE：**用于更新表中的数据。

```
<span><span>UPDATE</span> table_name </span>
```

在 table\_name 表中，找到满足 condition 条件的行，并将这些行的 column1 列更新为 value1，column2 列更新为 value2。

**DELETE：**用于删除表中的数据。

```
<span><span>DELETE</span>&nbsp;<span>FROM</span>&nbsp;table_name&nbsp;<span>WHERE</span>&nbsp;condition;</span>
```

**四、函数与聚合操作**

**COUNT：**用于返回匹配条件的行数。

```
<span><span>SELECT</span> <span>COUNT</span>(column_name) <span>FROM</span> table_name;</span>
```

**SUM：**用于返回列的总和。  

```
<span><span>SELECT</span> <span>SUM</span>(column_name) <span>FROM</span> table_name;</span>
```

**AVG：**用于返回列的平均值。  

```
<span><span>SELECT</span> <span>AVG</span>(column_name) <span>FROM</span> table_name;</span>
```

**MIN：**用于返回列的最小值。  

```
<span><span>SELECT</span> <span>MIN</span>(column_name) <span>FROM</span> table_name;</span>
```

**MAX：**用于返回列的最大值。  

```
<span><span>SELECT</span> <span>MAX</span>(column_name) <span>FROM</span> table_name;</span>
```

**五、子查询与联接**  

![图片](https://mmbiz.qpic.cn/mmbiz_png/vqlbVFl5Jn1k4XasuAae1vxS7E5VZztkwMjx4sxmPMqrOtSXdpGLmyquVHX1iaYQ3QVgwl3xDsyF9VLPuzdUIVA/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

**INNER JOIN：**用于返回两个表中都存在的记录。

```
<span><span>SELECT</span> column1, column2 <span>FROM</span> table1 </span>
```

从 table1 和 table2 中选择满足连接条件的行，返回 column1 和 column2 这两列的数据。

内连接只有当两个表中都有匹配的行时，结果才会包含这些行。

**LEFT JOIN：**用于返回左表中的所有记录和右表中的匹配记录。

```
<span><span>SELECT</span> column1, column2 <span>FROM</span> table1 </span>
```

从 table1 选择所有行，并包括 table2 中与 table1 指定列值匹配的行，如果 table2 中没有匹配的行，那么结果集中 table2 的列将显示为 NULL。

**RIGHT JOIN：**用于返回右表中的所有记录和左表中的匹配记录。

```
<span><span>SELECT</span> column1, column2 <span>FROM</span> table1 </span>
```

从 table2 选择所有行，并包括 table1 中与 table2 指定列值匹配的行，如果 table1 中没有匹配的行，那么结果集中 table1 的列将显示为 NULL。

右连接查询通常用于当 table2 是主要的数据源，而 table1 是补充数据源时。

**FULL JOIN：**用于返回两个表中所有记录，不管是否匹配。

```
<span><span>SELECT</span> column1, column2 <span>FROM</span> table1 </span>
```

从 table1 和 table2 中选择所有行，包括两个表中所有匹配和不匹配的行，如果某个表中没有匹配的行，那么结果集中该表的列将显示为 NULL。

全外连接查询通常用于需要从两个表中获取所有数据，而不考虑它们之间是否存在匹配关系的情况。

**SUBQUERY：**用于在查询语句中嵌套另一个查询。

```
<span><span>SELECT</span> column1 <span>FROM</span> table_name </span>
```

从 table\_name 表中选择那些其 column2 列的值等于子查询返回的值的行的 column1 列。

**六、高级操作**  

**UNION：**用于合并两个或多个 SELECT 语句的结果集。

```
<span><span>SELECT</span> column1 <span>FROM</span> table_name1 </span>
```

将 table\_name1 和 table\_name2 两个表中 column1 列的值合并为一个结果集，并且结果集中不会有重复的行。

![图片](https://mmbiz.qpic.cn/mmbiz_png/vqlbVFl5Jn1k4XasuAae1vxS7E5VZztkqXbShbPYtQtibBmbHvRuhUqXkeyibJvPFjVQNIPnGOVhibQhhVA4ak5vA/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

**CASE：**用于实现条件逻辑。

```
<span><span>SELECT</span> column1,</span>
```

在查询 table\_name 表时，根据列 column1 或其他列的值与 condition1 或 condition2 的匹配情况，返回相应的 result1 或 result2，如果都不匹配，则返回 result。

CASE 表达式允许你在 SQL 查询中根据多个条件进行数据转换或选择不同的值。

**INDEX：**用于创建索引以加速查询。

```
<span><span>CREATE</span>&nbsp;<span>INDEX</span>&nbsp;index_name&nbsp;<span>ON</span>&nbsp;table_name&nbsp;(column1,&nbsp;column2);</span>
```

在 table\_name 表上创建一个名为 index\_name 的索引。

**七、性能优化与安全性  
**

**EXPLAIN**：用于查看查询的执行计划。

```
<span><span>EXPLAIN</span> <span>SELECT</span> column1 <span>FROM</span> table_name <span>WHERE</span> condition;</span>
```

**TRANSACTION**：用于处理事务。

```
<span><span>START</span> <span>TRANSACTION</span>;</span>
```

**GRANT：**用于授予用户权限。  

```
<span><span>GRANT</span> <span>SELECT</span> <span>ON</span> database_name.table_name <span>TO</span> <span>'user'</span>@<span>'host'</span>;</span>
```

**REVOKE：**用于撤销用户权限。

```
<span><span>REVOKE</span> <span>SELECT</span> <span>ON</span> database_name.table_name <span>FROM</span> <span>'user'</span>@<span>'host'</span>;</span>
```
