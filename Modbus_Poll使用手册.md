# Modbus Poll使用手册
## 软件下载链接
https://github.com/TongHaiMCU/User_Manual/blob/main/Modbus%20Poll.zip

## 标准格式
https://github.com/TongHaiMCU/User_Manual/blob/main/Modbus_poll_%E6%A0%87%E5%87%86%E6%A0%BC%E5%BC%8F.mbp

### 1.点击`Connection -> Connect `。按照如下设置（链接单片机后，软件自动选择，也可以手动选择。）
| 按钮 | 
| -----|
|COM 串口选择（根据usb接口不同，每次显示的也不同）|
|19200波特率|
| 8bit数据 |
|  偶校验（Even Parity）|
| 1停止bit |
| Response Timeout ：1000 |

![image](https://user-images.githubusercontent.com/43512109/181444070-f95ac026-8887-4200-af3a-d8abe252829f.png)

### 2.点击 `Setup -> Read/Write Definition`
| 按钮 | 效果 |
| -----| ----- |
| Slave ID  | 你的单片机的通讯地址 |
| Function  | 选择03即可 |
| Address  | 从1开始显示 |
| Quantity  | 显示的数据有xx个 |
| Scan Rate  | 每隔1000ms去通讯/扫描一次 |
| Fit to Quantity  | 适合的行数 |
| PLC Address（Base 1）  | PLC那里从1开始，而不是从0开始 |

![image](https://user-images.githubusercontent.com/43512109/181444832-c62495de-75e2-4560-a682-c133ad7068e5.png)


## Real Time Charting(实时图表)
[官方教程](https://www.modbustools.com/poll_chart.html)

## 实验前导出Excel数据
### `Setup -> Excel Log` 。`rate`是`1s`一组数。`10000`个`logs`是记录`10000组`数据。（根据实验需求上述两个选项可随时改变）
![image](https://user-images.githubusercontent.com/43512109/181456756-09158ce9-092d-4045-8b52-0b4665e49578.png)


## 破解
### 点击 `Connection -> Connect and enter key`
    输入破解码 5A5742575C5D391A17627B6C010350
