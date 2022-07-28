# STC官方网站
http://www.stcmcudata.com/
# 下载器所在页面
![image](https://user-images.githubusercontent.com/43512109/181432275-8989d8db-2d22-491e-b862-22ee068342d7.png)
# 安装后界面
![image](https://user-images.githubusercontent.com/43512109/181432169-9507ac98-f9a3-4fcd-8f59-7afe081ee6e1.png)
# 一.使用说明
## 1.先将软件按照如下所示修改
- 1是单片机单片机的芯片
- 2是串口
- 3是波特率
-4是下载程序的设置
![image](https://user-images.githubusercontent.com/43512109/181432313-fa10049d-ae68-48c7-92fb-dec5e78045fe.png)
## 2.串口设置

### 每个人每次使用的USB口不一样，导致此处`串口`号也不一致。**软件会自动寻找到串口**。
![image](https://user-images.githubusercontent.com/43512109/181432334-e580dabf-8f6d-402e-af0b-07b7f795f5f3.png)

### 插上USB后，`自动显示串口`，如下图所示

![image](https://user-images.githubusercontent.com/43512109/181432436-5e5d9d25-f143-40e8-bfd5-22a9df543c4e.png)

## 3.往单片机中下载程序
### 先将`单片机`电源断电，`单片机`的所有开关关闭，将`单片机`、`下载器`、`电脑`连接好后，点击`打开程序文件`，找到单片机程序（`.hex文件`）所在位置，点击`下载/编程`。
![image](https://user-images.githubusercontent.com/43512109/181432443-073a328a-6610-45a0-9789-8a0f0c7dd920.png)

### 切换到`单片机`上。

| 板子| 下载程序的方法|
| ------ | ------ |
| 绿色板子 | `黑色开关`打开 |
| 黄色板子 | `蓝色按钮`（复位开关处），打开|

### 在下载过程中，`USB下载器`的`红灯`会一直闪烁，这就证明下载正常。等待`STC软件`显示`完成`，如下图所示。则程序已下完。

## 4.EEPROM
### 这里一般不勾选，当我们确认要擦除`EEPROM`的数据的时候，`勾选`后，**程序下载两次**，即可擦除成功。
![image](https://user-images.githubusercontent.com/43512109/181432471-c3a84bc8-090a-436d-b5c5-98bb7880fe89.png)

# 二.注意事项及出现的问题
## 1.下载失败???
- 看看`USB下载器`与`单片机`的下载口接的对不对？
- `USB下载器`是不是坏了？
- 一开始所有`开关`没关闭？
- 是不是提前打开`复位开关`（下载程序的开关）？
- `电脑USB`口是不是损坏了？（这个是会出现的）
## 2.检查线路、接口、下载器后都没问题，依旧下载失败？
- 将`USB下载器`与`单片机`断开后过5s，重新下载程序操作。

