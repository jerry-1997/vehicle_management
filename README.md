
### 车辆管理系统接口
### -----------基本实体-----------
#### 车辆、司机、员工

### ----------扩展车务实体---------
### 故障、加油、保养、维修、事故、保险、年检、警报

### ----------扩展出车实体---------
### 申请、行程、工况、排班、用车、派车

### -------------实体属性----------
### 车辆信息表：车辆 id；车牌号；品牌；类型；车名；忙闲；车龄；所属部门；车辆所属人；车架号；发动机号；使用性质；注册日期；发证日期；
### 员工信息表：员工 id；姓名；年龄；性别；生日；住址；身份证号；电话；部门；工龄；
### 司机信息表：司机 id；员工 id；驾照号；取证时间；忙闲；

### 车辆信息表员工信息
### 故障车辆信息表：故障 id；车辆 id；操作员；时间；地点；类型；状态；备注；
### 事故车辆信息表：事故 id；车辆 id；时间；地点；类型；处理状态；备注；
### 修理车辆信息表：修理 id；故障 id；事故 id；时间；地点；修理类型（保险还是自费）；费用；备注；
### 加油车辆信息表：加油 id；车辆 id；时间；费用；油号；单价；加油量；加油站；仪表盘里程；剩余里程；备注；单据信息；
### 保养车辆信息表：保养 id；车辆 id；保养单位；本次保养日期；本次保养里程；下次保养日期；下次保养里程；保养项目;花费；备注；单据信息；
### 保险车辆信息表：保险 id；车辆 id；保险单位；商业保险费；交强保险费；其他保险费；保险开始日期；保险结束日期；备注；单据信息；
### 年检车辆信息表：年检 id；车辆 id；年检日期；下次年检日期；年检费用；年检地点；备注；单据信息；
### 警报车辆信息表：警报 id；车辆 id；报警时间；报警消息；

### 申请信息表：申请 id；员工 id；申请车辆 id；所属部门；用车信息；驾车方式；申请时间；申请状态；
### 行程信息表：行程 id；车辆 id；行程；备注；
### 排班信息表：排班 id；车辆 id；状态；预约提示；备注；
### 派车信息表：id；车辆 id；司机；派车时间；出发点；目的地；用车理由；内部乘车人；外部乘车人；备注；
