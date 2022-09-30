# 磁编码器

> 前几天(22.9.28)才知道MagnTek是中国公司，去年看了一年的英文手册……

### mt6701

#### 优点

- 便宜，小批量购买6元/片
- ABZ resolution最高为1024PPR，已经能够满足很多项目的需求
- 能检测z轴的磁场变化，可以做按压式开关（旋钮）
- 4.5-5.5V均可烧写EEPROM，无需额外升压

#### 缺点

这么便宜就不列缺点了（



### mt6825gt

#### 优点

- ABZ resolution is user programmable from 1~4096 PPR
-  build in MTP memory to program resolution, zero position, zpulse width etc. parameters.

#### 缺点

- 小批量售价高，25元/片，对于一些项目来说太贵了
- 进行MTP编程时HVPP需达到7-7.2V，对于很多5V供电的板子来说需要额外升压
- 

### mt6835

mt6825gt的升级版

#### 优点

- ABZ resolution达到了16384 PPR，可以读取更高精度的数据，并且可编程