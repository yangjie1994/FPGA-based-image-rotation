# FPGA-based-image-rotation
base on PANGO PGL22G

#4.1版本:
 *使用最近邻差值法，输出图像无滤波
 *单像素读使用axi port2，连续读出写入使用port1
 *单像素读出整帧写入分辨率800*600
 *通过串口读取角度角度
 *实现根据角度摄像头旋转角度任意角度旋转图像
 *图像使用块方式储存，提高帧率
 
#5.0版本:
 *使用双线性插值法
