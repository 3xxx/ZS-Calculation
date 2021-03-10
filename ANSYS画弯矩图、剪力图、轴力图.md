# ANSYS画弯矩图、剪力图、轴力图(以BEAM188为例)

BEAM188单元输出数据项目和序列号

| 项目 | 命令  |  I   |  J   |
| :--: | :---: | :--: | :--: |
|  Fx  | SMISC |  1   |  14  |
|  My  | SMISC |  2   |  15  |
|  Mz  | SMISC |  3   |  16  |
| SFz  | SMISC |  5   |  18  |
| SFy  | SMISC |  6   |  19  |

## 设定Element Table

`General PostProc`-> `Elemnet table` -> `Define Table`

定义Lable, 然后从下面的选项框中选择By Sequence num ，右边选择SMISC，在下方输入对应的编号。

![define-table](images\define-table.png)
![define-table2](images\define-table2.png)

## Plot Element Table
在`General PostProc`->`Plot Result` -> `Contor Plot` -> `Line Element Res`中选择对应的I和J
![plot-element-table](images\plot-element-table.png)
