### 项目介绍
此机器人可用于审核具有有效产品的用户用户加入指定的Telegram售后群组

适用的系统有WHMCS（包括但不限于，可根据接口返回值自己编写指定的数据库接口文件）。SSPANEL也有...处于风险考虑，不公布

### 使用方法

将机器人拉入群组并授予管理权限

编辑config.py文件，修改配置，ID可使用@getmyid_bot或者@get_useridbot获取

添加管理员用户ID，注意，群组里面的其他管理机器人也需要添加

使用 python3 main.py 运行程序

常规的python项目部署步骤，不赘述

### 适配新的系统

加入TG交流群组 (@devourbots)[https://t.me/devourbots]

如需适配其他系统，请将数据库相应字段示例导出为可导入的sql文件发送给管理员
