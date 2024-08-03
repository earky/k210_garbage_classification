## 1.准备任务

- **软件：**maixpyide

- **硬件：**maix-bit，摄像头，LED屏幕，4个LED小灯，1个舵机，读卡器和TF卡(如果没有可以通过kflash_gui将文件烧录进去，再修改文件位置即可)

## 2.接线图

黄(其它垃圾)-3	 绿(厨余垃圾)-2	 红(有害垃圾)-1	 蓝(可回收物)-0 	舵机-17 （记得接3.3V电压，5V电压可能会击穿芯片）

### 3.说明

- 通过舵机转动不同的角度来模拟打开不同垃圾桶的操作，所以你如果有4个舵机那就更好了
- 该模型只选取了部分垃圾进行测试，并未将全部垃圾都训练过，垃圾样式和数量如下
  - 厨余垃圾：八宝粥       240		冰糖葫芦     210
  - 可回收物：玻璃杯       210                充电头         209             电磁炉        209
  - 其它垃圾：PE塑料袋   210                一次性棉签 210
  - 有害垃圾：灯               210                电池	     210 









## 1.Preparatory task

- **software：**maixpyide

- **hardware：**maix-bit，Camera, LED screen, 4 small LED lights, 1 steering gear, card reader and TF card (if not, you can burn the file through kflash_gui, and then modify the file location)

## 2.Wiring diagram

Yellow (other garbage)-3	 green (kitchen waste)-2	 red (harmful waste)-1	 blue (recyclables)-0 	steering gear -17 (remember to connect 3.3V voltage, 5V voltage may break down the chip)

### 3.Instructions

- By turning the steering gear at different angles to simulate the operation of opening different garbage cans, so if you have 4 steering gear that is even better
- This model only selected part of the garbage for testing, but did not train all the garbage. The garbage styles and quantities are as follows
  - Kitchen waste:              Eight treasures porridge       240		Rock sugar gourd                     210
  - Recyclables:                  Glasses                                     210                Charger                                       209                                                                                                              .                                       Induction cooker                    209
  - Other garbage:             PE plastic bags                       210                 Disposable cotton swab          210 
  - Hazardous waste:        Lamp                                        210                Battery	                                 210 

