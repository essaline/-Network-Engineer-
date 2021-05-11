### 1.1   OSI参考模型

1.

物理层(physical layer)
位于OSI/RM模型底层，提供透明的比特流传输。

连接方式：半双工或是全双工。

传输方式：同步或是异步。

通过协议定义了网络的机械特性、电气特性、功能特性和规程特性。
规程特性：指明各种可能事件出现的顺序。

DCE(data communication equipment)和DTE(data terminal equipment)
DTE:常见的有路由器、PC、终端。
DCE：CSU/DSU、NT1、广域网交换机、MODEM。
区别：DCE提供时钟、DTE不提供时钟；DTE的街头是针头，DCE的接头是孔头。

2.
数据链路层(data link layer)
链路是相邻两节点之间的物理线路。

数据链路层应具有的功能：
链路连接的建立、拆除、分离；
帧定界和帧同步；
顺序控制；
差错检测、恢复。

