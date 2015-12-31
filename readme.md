## 服务器主机地址
<table>
    <tr>
    	<th align="left">主机名称</th>
		<th align="left">IP地址</th>
		<th align="left">设计功能</th>
	</tr>
	<tr>
		<th align="left">namenode</th>
		<th align="left">10.125.110.166</th>
		<th align="left">主节点，NameNode</th>
	</tr>
		<th align="left">resourcemanager</th>
		<th align="left">10.125.110.163</th>
		<th align="left">主节点，ResourceManager</th>
	</tr>
	</tr>
		<th align="left">datanode1</th>
		<th align="left">10.125.110.121</th>
		<th align="left">从节点，DataNode，NodeManager</th>
	</tr>
	</tr>
		<th align="left">datanode2</th>
		<th align="left">10.125.110.115</th>
		<th align="left">从节点，DataNode，NodeManager</th>
	</tr>
	</tr>
		<th align="left">datanode3</th>
		<th align="left">10.125.110.100</th>
		<th align="left">从节点，DataNode，NodeManager</th>
	</tr>
	</tr>
		<th align="left">datanode4</th>
		<th align="left">10.125.110.66</th>
		<th align="left">从节点，DataNode，NodeManager</th>
	</tr>
</table>


## 已安装软件：
* JDK 1.8 (/usr/local/jdk1.8.0_65)
* Hadoop 2.6.0 (/usr/local/hadoop-2.6.0)
* Hive 1.2.1 (/usr/local/apache-hive-1.2.1-bin)
* HBase 1.1.2 (/usr/local/hbase-1.1.2)

## 登录工具：ssh远程登录
* Linux: Console即可
* Windowns: Xshell
* VMware vSphere Client

## 使用约定(请大家自觉遵守，定期拆除违章"建筑")

1. 已配置好的环境请勿随意改动，若有改动，请将改动之处append至log.txt文件处，并commit此文件

2. 各组的代码，项目，模型，以及各种中间产物请放置在主机namenode的对应目录下:
    *刘润涛组: /home/dachuang/workspace/liuruntao
    *刘昕彤组：/home/dachuang/workspace/liuxintong

3. Hive与HBase命名规范:
    *所有字母均小写，单词以下划线分割
    *database: db + "_" + 组长名 + "_" + DB名称, e.g: db_liuruntao_db1
    *table: 组长名 + "_" +  表名， e.g: liuruntao_table1