# 实验室注意事项

## 样品排布

- 样品台边左侧缘存在X轴无法到达的盲区，而上下可能因样品台横梁遮挡下部光源，因此样品点应尽量避开上下及左侧边缘。

## Mapping

- 空间分辨率：横向为`移动速度*T` (所有元素一次分析的总积分时间)，纵向分辨率则等于激光的斑束，扫描速度和斑束主要受样品大小及分析要求控制。
- 移动速度：激光扫描采用线扫描，其移动速度>激光斑束，一般`1-1.5`倍束斑大小，但小于200um可以将移动速度降到`3-5um/s`以提高横向分辨率。
- 扫描时长：`0.5-2.5`小时，一般`1-1.5`小时。如果时间太短则分辨率较差，时间太长则仪器的漂移校正存在一定问题。
- 标准样品：`30-40`秒，束斑与样品一致。
- 质谱积分时间：累计分析时间不宜超过`0.3s`，单个元素积分时间`3ms-10ms`。
- 样品的选择：多矿物扫描区为方形即可，单矿物一般基于矿物形状来进行选择。

## 质谱方法设定

- 点分析积分周期不超过`0.5s`，采样时间`60s`
- 面扫描积分周期不超过`0.3s`，采样时间`9999s`
- 检查背景信号：点击质谱仪页面`调谐`，使用`30um`束斑对`SRM610`进行点剥蚀，保证`U238`信号高于`20000`，同时在不剥蚀的情况下`Si29`的背景信号在`2000`以下。

!>由于ICP-MS等离子体的特点，以下元素在测试中需要指定

- **Si**：选择 `29 Si`
- **Ca**：选择 `44 Ca`
- **Ti**：选择 `49 Ti`
- **Fe**：选择 `57 Fe`
- **Se**：选择 `77 Se`

## 质谱仪切换LA引入

 - 点击`硬件`，右键`样品引入`，选择`属性`，将`样品引入`下拉切换为`LA`，关闭。
 - 选择工具栏中的`工具`，选择`MassHunter设置`，选择`数据选项`，勾选`数据采集（不进行数据分析）`
 - 将雾化器更换为LA传入喇叭口，将气路插入`CARRIER`管口（最右侧）

## 常用标样一览

![](/static/img/srm.jpg)

![](/static/img/srm2.jpg)

## 激光器真空参数

![](/static/img/laser-evacuate.jpg)