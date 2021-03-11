[首页](./readme.md) | [埋件](./埋件计算类.md) | [外挂](./外挂计算类.md) | [内爬钢梁](./内爬钢梁计算.md) | [附着](./附着计算.md) | [压杆](./压杆校核.md) | [风载](./风载.md)
# ANSYS经典模式自定义工具栏

ANSYS经典模式默认的工具栏可以根据工作需要自由定义常用的命令按钮

![toolbar](images\toolbar.png)



用到的文件：

1. [MyPrepare.mac](macs/MyPrepare.mac)

2. [start.ans](macs/start.ans)

下载以上两个文件，放在目录：

`C:\Program Files\ANSYS Inc\v191\ansys\apdl`

覆盖原文件即可。(不同版本目录名称略有不同，v191是当前安装的版本号，18的话可能是v18*)

## 工具栏命令解释

* PREP——进入前处理

* MYSET——自定义参数设置，单元类型，材料属性

* BEAM_SEC——添加梁单元截面

* Mesh——划分网格工具

* Num_Cmp——编号压缩

* Accel——添加加速度

* SOL——进入求解处理

* D_K——添加关键点位移约束

* F_K——添加关键点载荷

* Del_DK——删除关键点位移约束

* SOLVE_LS——求解

* POST——进入通用后处理

* DISP——显示总位移云图

* DISP_X——X向位移

* DISP_Y——Y向位移

* DISP_Z——Z向位移

* EQV——第三强度理论合应力云图

* REA_SOLU——显示节点反力

