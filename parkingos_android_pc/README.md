# ParkingOS_cloud
<h1>车牌识别车场收费前端</h1></br>
产品简介：此收费系统是基于安卓平台开发的，既配合车场服务器可以完成车场的收费功能，也可以直接连接云端进行收费，生成结算订单、月卡办理、价格设置这些常用操作都放在服务器端设置，安卓端负责读取和信息的提交。

运行环境：安卓设备，系统4.2以上，目前适配了安卓电视棒，小米平板，技德厂家的Remix mini。

外置硬件对接：   摄像头：适配了臻识的车牌识别一体机。可以在此基础上适配其它品牌摄像头，遵守标准接口协议即可。
                LED屏：控制卡适配了清源信息的语音显示一体卡，其它品牌的可以自行遵循TCP/IP协议来对接。
                道闸：目前是通过摄像头转发开关量信号负责开闸，地感线圈负责回落。