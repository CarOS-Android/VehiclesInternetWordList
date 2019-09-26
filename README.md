# VehiclesInternetWordList
This is repo to maintain all Vehicle Project Special words.

## Word Description
HMI - Human Machine Interface， 在汽车上，特指机车系统上，包括但不限于中控，仪表，HUD等等车内人机交互系统。
IoV - Internet of Vehicles，车联网，物联网(IoT)的一种，将车辆，路面信息，基础设施，网络，云等连接到一起。
V2X - Vehicle to X，车与万物（X是指的everything）

* V2V - Vehicle to Vehicle，车与车
* V2P - Vehicle to Pedestrian，车与人
* V2N - Vehicle to Network，车与网络
* V2C - Vehicle to Cloud，车与云

IVI - In-Vehicle Infotainment，车内娱乐系统
ECU - Engine control unit/module， 电子控制单元

* TCU - Transmission Control Unit
* EMS - Engine Management Systems
* BCM - Body Control Module
* BMS - Battery Management System
* HAVC - Heat, Air Ventilation, and Cooling
* SRS - Airbag System

CAN bus - Controller Area Network，汽车内部通讯网络系统，将一堆节点（node），也就是ECU串联在一起进行通讯

* CAN FD - Flexible data rate can protocol

OBD2 - On-board diagnostics，用来诊断跟上报汽车异常，根据诊断码(DTCs diagnostic trouble codes)

ADAS - Advanced Driver Assistance Systems，高级驾驶辅助系统

## Words English - 中文(A-Z)
### B报警信息
* Fuel level low: 燃油低提醒

### C车辆属性 - Vehicle Properties
#### B变速箱: Gearbox
* Gear selection: 当前档位
    * Gear Neutral: N档
    * Gear Revers: R档
    * Gear Park: P档
    * Gear Drive: D档
    * Gear 1,2..: 1,2..档
    
#### D灯光：Light
* Headlights: 近光灯
    * On: 开启
    * Off: 关闭
    * Daytime running: 日行灯
    * Automatic: 自动大灯
* High Beam Lights: 远光灯
* Hazard Lights: 示宽灯
* Fog Lights: 雾灯 
    * Front(前) 
    * Rear(后)
* Turn Signal Light: 转向灯
    * Left(左)
    * Right(右)
* Cabin lights: 氛围灯
* Reading lights: 阅读灯
    
#### F发动机：Engine
* Temperature of engine coolant: 冷却液温度
* Engine oil level: 机油量
* Engine oil temperature: 机油温度
* Engine RPM: 发动机转速
* Speed: 当前时速

#### G高级驾驶辅助系统：ADAS
* Adaptive Cruise Control (ACC)：自适应巡航
* Adaptive Light Control (ALC)：自适应灯光
* Automotive Navigation System(ANS)：自动导航系统，基于GPS和交通信息TMC(Traffic Message Channel)
* Blind-Spot Monitoring (BSM)：盲点监测系统
* Collision avoidance system/Precrash system：防撞系统
* Driver drowsiness detection：驾驶员疲劳探测
* Driver Monitoring System (DMS)：驾驶员监测系统
* Forward Collision Warning (FCW)：前撞警告
* Head-Up Display (HUD)：平视显示器
* Hill descent control：下坡控制
* Intelligent Speed Adaptation (ISA)：智能车速适应/电子警察系统
* Lane change assistance：变道辅助
* Lane keep assistance：车道保持
* Lane Departure Warning (LDW)：车道偏移报警系统
* Night Vision System (NVS)：夜视系统
* Pedestrian Detection System (PDS)：行人探测系统
* Park Assist (PA)：泊车辅助
* Road Sign Recognition (RSR)：道路信号识别
* Surround-View Cameras (SVC)：环视相机
* Autonomous Emergency Braking (AEB)：自主紧急制动

#### K空调制冷制热通风: HAVC(Heat, Air Ventilation, and Cooling)
* Fan speed: 风扇速度
* Fan speed RPN: 风扇转速
* Fan direction: 出风方向
    * Direction Face: 面部
    * Direction Floor: 底部
    * Direction defrost: 除雾
* Current temperature: 当前温度
    * Celsius: 摄氏温度
    * Fahrenheit: 华氏温度
* Set temperature: 预设温度
* Defrost: 除雾
* AC on/off: AC开关
* Recirculation: 循环方式
    * On: 内循环
    * Off: 外循环
* Automatic Recirculation: 自动循环
* Dual: 分区空调
* Seat heating/cooling: 座椅加热/制冷
* Seat ventilation: 座椅通风
* Side Mirror Heat: 后视镜加热
* Steering Wheel Heating/Cooling: 方向盘加热/制冷

#### N能源（燃油/电）: 
* Fuel Type: 燃料种类
    * Leaded: 加铅汽油(Leaded
 gasoline)
    * Unleaded: 无铅汽油(Unleaded gasoline)
    * Diesel: 柴油
    * E85: 乙醇汽油(85% ethanol/gasoline blend)
    * LDP: 液化石油气(Liquified petroleum gas)
    * CNG: 压缩天然气(Compressed natural gas)
    * LNG: 液态天然气(Liquified natural gas)
    * Electric: 电动
    * Hydrogen: 混动
* Level: 燃料量
    * Fuel level: 汽油余量（以英里或者公里数表示）
    * EV Battery level: 电池余量(WH以瓦特每小时表示)
* Fuel volume: 邮箱容量
    * Liter: 公升
    * Gallon: 加仑
* EV Battery: 电量
    * Watt/Hour(Wh): 瓦特每小时
    * Ampere/Hours(Ah): 安培每小时
    * Kilowatt/Hour(kWh): 千瓦特每小时
* Port: 
    * Location: 燃油盖/充电口的位置，一般在后右，后左，前左，前右等位置
        * Fuel door: 燃油盖
        * Ev port location: 充电口
    * State: 状态
        * Door open: 燃油盖打开
        * Ev charge port open: 充电口打开
        * Ev charge port connected: 正在充电
        
#### Q汽车座舱: Cabin
* Driver Seat: 驾驶员座椅
* Parking brake state: 手刹状态
* Auto-apply parking break: 自动手刹
* Ignition state: 点火状态
    * Lock: 车轮锁定
    * Off: 关闭
    * ACC: 只启动部分功能，仪表盘跟引擎没有启动
    * On: 启动
* Door lock: 门锁
* Mirror: 后视镜
* Mirror fold: 后视镜折叠
* Mirror lock: 后视镜锁定
* Seat memory: 座椅记忆
* Window lock: 车窗锁
* Hood: 引擎盖
* Rear: 车尾

#### Y仪表盘： Cluster
* Odometer: 里程表
    * Kilometer: 公里
    * Mile: 英里
* Range remaining: 剩余里程数（当前燃料可以支撑的）
* Steering angle: 方向盘转角
* Tire pressure: 胎压
    * Kilopascal: 千帕
    * PSI: 磅/平方英寸
    * BAR: 1 bar ≡ 100,000 Pa ≡ 100,000 N/m2
* ABS: 防抱死系统
* Traction control: 牵引力控制
* Outside temperature: 车外温度

## Vehicle Tech Rader - 车联网技术雷达，技术栈(Tech Stack)
### Technology
### Platform
### Framework & Language
### Tools

