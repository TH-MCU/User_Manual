# Modbus Poll使用手册
## 链接
### 1.点击`Connection -> Connect `。按照如下设置（链接单片机后，软件自动选择，也可以手动选择。）
| 按钮 | 
| -----|
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
| Fit to Quantity  | 切换行和列 |
| PLC Address（Base 1）  | PLC那里从1开始，而不是从0开始 |

![image](https://user-images.githubusercontent.com/43512109/181444832-c62495de-75e2-4560-a682-c133ad7068e5.png)


## Real Time Charting

## 导出Excel数据

## 显示标题

## 破解
