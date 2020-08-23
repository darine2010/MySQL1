# MySQL
Constraint
================
常见约束(创建表时使用)
______________
一、含义
一种约束，为保证表中数据的准确性和可靠性。<BR>
二、六大分类<BR>
1、not null：非空约束，字段性不可为空，*号标识的内容。<BR>
2、DEFAULT：默认值。<BR>
3、primary key（PK）：唯一+非空。如：学号、员工编号等。<BR>
4、unique：唯一性约束，可为空。如：邮箱。<BR>
5、foreign key(FK)：外键约束。 <BR>
用以保证从表内中该字段内的值必须来自于主表中对应字段内的值（通常为主键）。<BR>
如：学生表内majorid,员工表内departmentid,jobid等。<BR>
6、CHECK:检查约束，目前MySQL不支持、Oracle支持。如：年龄、性别。<BR>
三、添加时间<BR>
1.建表时<BR>
2.修改表时。<BR>

四、约束分类<BR>
1.列级约束：<BR>
	位于字段尾部，约束本字段。<BR>
	六大约束均支持，外键约束无效。<BR>
2.表级约束<BR>
 除了 not null、default，其他均支持。<BR>
