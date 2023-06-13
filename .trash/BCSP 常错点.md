1. Mysql 
	1. 事务四大特性
		- 原子性、一致性、隔离性、持久性
	2. 索引:
		- 主键、唯一、普通、全文索引
1. Linux 指令
	1. 显示文件搜索包含内容行号的指令
		- `grep -n 'search' file`
		- 行数 `grep -c`
	2. Linux 查看当前用户指令/显示自身用户名
		- `whoami`
	3. Linux 创建新文件的命令
		- `mkdir`
	4. Linux 查看所有进程的详细信息 
		- `ps -H` 查看所有进程的详细信息
		- `ps -N` 查看指定进程的详细信息，N 为进程号
		- `ps -A` 查看所有进程
1. Java 生成随机数
	```java
	System.out.println((int) (Math.random() * 10));
	int i = new Random().nextInt(10);
	```
4. Java 中的枚举
	1. `name()`: 返回枚举常量的名称
	2. `ordinal()`: 返回枚举常量的序数
	3. `valueOf()`: 用于将一个字符串转为对应的枚举常量
	4. `values()`: 返回枚举类型的对象数组