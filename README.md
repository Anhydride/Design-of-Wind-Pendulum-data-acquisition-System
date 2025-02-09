<h1>风力摆数据采集系统</h1>
&emsp;&emsp;利用加速度计模块 MPU-6050 测出风力摆角度传感器的数据，使用 STC89C52RC 单片机， 从 MPU-6050 读入倾斜角、角速度等数据后，再通过 LCD1602 进行数据显示。<br>
&emsp;&emsp;使用 STC89C52RC 单片机，从 MPU6050 中读取出加速度和角度。 为了便于数据读取，应用了 LCD1602 显示 A（从左到右分别是 x、y、z 轴加速度）和 G（从左到右分别是 roll、pitch、yaw 轴加速度），更加直观便捷。<br>
&emsp;&emsp;开发前期首先在STC89C52单片机开发板上试运行代码，发现显示屏存在显示对比度低、亮度暗的问题。后面对代码进行优化修改后移植到 STC89C52RC 芯片上，这一情况得到改善。<br>
