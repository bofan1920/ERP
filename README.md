# ERP

ERP系统高可用：主要通过Flask启动一个app，通过虚拟VIP模拟http://172.16.5.23/data故障转移，未实现附件的同步、共享存储等
PostgreSQL主从同步：主要涵盖PostgreSQL主从同步
PostgreSQL安装、高可用和故障转移：主要演示灾难恢复和故障转移。未实现patrion+etcd分布式故障转移功能
