# 电控组第二次培训作业

* **宋宇乐**

* ***20263004494***

  <video src="D:\rm\流水灯作业\video_20261025_092814.mp4" controls=""></video>

![image-20261025094058079](C:\Users\hp\AppData\Roaming\Typora\typora-user-images\image-20261025094058079.png)

定义变量state(记录状态)和i(计算时间差)

用GetTick获取当前时间 减去上次被GetTick赋值的时间i, 判断是否>=500, 

每过500ms 将当前时间赋值给i 并将state++, 0 1 2分别对应LED0 1 2 state>2时又回归到0 重复过程